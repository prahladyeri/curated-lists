# Checklist: Publishing a package to PyPi

1. Register an account on [PyPi](https://pypi.org/) if you don't have one.
2. Install `setuptools` and `twine` if they aren't already. Create a `setup.py` in your source folder as follows (check out [setuptools docs](https://setuptools.readthedocs.io) for more detailed setup options):

		# replace:
		# <your_package> with your actual package name.
		# <you> with your name.
		# <your_email> with your public email address.
		# <your_github_repo_url> with your github project's url.
		from setuptools import setup, find_packages
		
		s = setup(
			name="<your_package>",
			version="1.0.0",
			license="MIT",
			description="Foo App",
			url='<your_github_repo_url>",
			packages=find_packages(),
			install_requires=[],
			python_requires = ">= 3.4",
			author="<you>",
			author_email="<your_email>",
			)


3. Optional: Bump up the version number (and git commit) if this isn't your first release:

	git add . && git commit -m "chore: released 1.0.1" && git push

4. Run `python setup.py sdist` from your source folder.
5. Optional: Sign the newly generated package with your `gpg` signature:

		gpg -a --detach-sign dist/<your-package>-1.0.0.tar.gz
	
6. Upload your package using `twine`:

		twine upload dist/<your-package>-1.0.0.tar.gz -u <your-pypi-username> -p <your-pypi-password>
	
	If you've signed the package, then you may also add the signed .asc file as the argument like this:
	
		twine upload dist/<your-package>-1.0.0.tar.gz dist/<your-package>-1.0.0.tar.gz.asc -u <your-pypi-username> -p <your-pypi-password>

7. Visit <https://pypi.org/project/your_package> to verify that your package has been uploaded.
8. Run `pip install <your_package>` to verify the package installation using pip package manager.
9. Optional: Tag the commit with the new version number:

		git tag "1.0.1"
		git push --tags