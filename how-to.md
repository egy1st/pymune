cd C:\Users\moham\Documents\GitHub\pymune

instructions at:
- https://packaging.python.org/en/latest/tutorials/packaging-projecpy -m pip install --upgrade pipts/

# update pip
- py -m pip install --upgrade pip


# Generating distribution archives
- py -m pip install --upgrade build
- py -m build


# Uploading the distribution archives
- install twine:
>  py -m pip install --upgrade twine
- upload all of the archives under dist: 
> py -m twine upload --repository pypi dist/*

note: you may use testpypi rather than pypi for testing purposes initially

# login for pypy repository
- enter you username and password for pypi repository

