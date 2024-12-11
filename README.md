# Getting Started Luxonis OAK

## Prerequisites

Python build and setuptools are required. It's recommended to use a virtual environment.

```bash
python3 -m venv venv
source ./venv/bin/activate
python -m pip install -U pip
python -m pip install build setuptools
```

(optional) Luxonis provides pre-built wheels of depthai which can be installed as follows:

```bash
python -m pip install --extra-index-url https://artifacts.luxonis.com/artifactory/luxonis-python-snapshot-local/ depthai
 ```

## Development

Install `dev` and `test` dependencies with an editable package for development:

```bash
python -m pip install --editable ".[dev,test]"
```

## Run luxonis depthai viewer

```bash
python3 -m depthai_viewer
```

## Build package

Run build command:

```bash
python -m build
```
