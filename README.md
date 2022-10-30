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

Use `poetry`

```bash
poetry init
```

Activate a virtual environment with `poetry`

```bash
poetry shell
```

Add new packages [`-D` for dev dependencies]

```bash
poetry add [-D] <package_name>
```

Remove a dependency

```bash
poetry remove <package_name>
```
