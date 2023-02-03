# Cookiecutter Mbed OS Library
[Cookiecutter](https://github.com/audreyr/cookiecutter) template for a Mbed OS
library.

## Requirements
Install `cookiecutter` from the command line:

```shell
pip install --user cookiecutter
```

## Usage
Generate a new Mbed OS library from template:

```shell
cookiecutter gh:catie-aq/cookiecutter_mbed-os-lib
```

## Template variables
- `project_name`: name of the project, eg. "My New Library"
- `project_short_description`: one-line description of the project
- `project_slug`: GitLab project slug (lowercase, hyphen-separated), eg. `my-new-lib`
- `library_name`: library main class name (Pascal case), eg. `MyNewLib`
- `base_name`: CPP source file name (without extension, lowercase, undescore-separated),
  eg. `my_new_lib`
- `copyright_holder`: copyright holder used in headers
- `copyright_year`: copyright year used in headers
- `open_source_license`: project license
- `create_repository`: if true, creates a Git repository, adds all files and makes first
  commit