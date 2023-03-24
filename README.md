# Cookiecutter Django Project Hatch Template

This is a cookie cutter template for creating Django projects with the following features already configured.

- [Hatch][ht] management tool with environs.
- Extensive pre-commit checks, including but not limited to:
    - shellcheck
    - pyupgrade
    - django-upgrade
    - djhtml
    - prettier
    - eslint
    - curlylint
    - black
    - blacken-docs
    - isort
    - flake8
    - interrogate
- Configuration done in pyproject.toml where supported, failing back to setup.cfg for libraries that do not support it.
- Docs via [MkDocs][mk]
- Project skeleton using adamchainz's [simple-core][sct] template.

## Usage

First, make sure you have cookiecutter installed on your machine. We recommend using pipx for this.

`$ pipx install cookiecutter`

Then run:

`$ cookiecutter gh:andrlik/cookiecutter-djangoproject-hatch`

Answer the questions when prompted and you'll have your project skeleton!

[ht]: https://hatch.pypa.io/latest/
[mk]: https://www.mkdocs.org
[sct]: https://github.com/adamchainz/django-startproject-templates