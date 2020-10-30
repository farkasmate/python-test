# test

## Add to project (Pipenv)

    [packages]
    test = { git = 'https://github.com/farkasmate/python-test' }

## Usage

    import test

## Run linter

    pipenv install --dev
    pipenv run pylint test

## Package

    pipenv run python setup.py sdist bdist_wheel
