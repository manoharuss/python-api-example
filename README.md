![GITHUB CI](https://github.com/manoharuss/python-api-example/workflows/GITHUB%20CI/badge.svg?branch=master)

# python-api-example

A flask based simple Python API template hooked to Github Actions CI.

## Setup

**Python version**

```

$ python --version

Python 3.7.4

$ pip --version

pip 20.1.1 from /Users/username/env/lib/python3.7/site-packages/pip (python 3.7)

```

**Install dependencies**

```sh

$ pip install -r requirements.txt

```

**Start app**

```

npm run lint

npm start

```


Head over to http://0.0.0.0:80/ for seeing locally served README.md.

### Continuous development

The CI builds on github actions are only triggered if a developer commit message contains the phrase - "build". The development commits that do not need a CI build to be triggered, just do not use the phrase `build` in commit messages.

