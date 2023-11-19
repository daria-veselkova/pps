# PPS - Python project skeleton

This is a bunch of useful templates, configs and scripts which can be used when starting a new Python project.
I will collect here only those things which helps me a lot in a real work.

## Git version control

Init a git repository in the root of the project

```bash
git init
```

Add a remote repository to be synchronized with

```bash
git remote add <repo_name>
```

## Dependency management

Use `poetry` (`pip install poetry`)

```bash
poetry init
```

Use necessary Python version

```shell
poetry env use 3.12.0
```

Activate a virtual environment with `poetry`

```shell
poetry shell
```

Add new packages [`--group dev` for dev dependencies]

```shell
poetry add [--group dev] <package_name>
```

Remove a dependency

```shell
poetry remove <package_name>
```
