# Cookiecutter Python Template 🍪
Cookie-cutter template for a basic Python project set-up, with boilerplate including some shiny modern development practices.

## How to Use 🔧
### Using Cookiecutter ✂️
There are several ways of using Cookiecutter templates, a quickstart guide can be found here: [Cookiecutter](https://github.com/cookiecutter/cookiecutter)

Once cookiecutter is installed, you can create a new project based on a template from a local template using:
- ```$ cookiecutter <path_to_template_folder>```

Or from a remote template using:
- ```$ cookiecutter <template_github_url>```

And if using a uv environment with cookiecutter installed, you can run:
- ```$ uv run cookiecutter <template_path_or_github_url>```

This should then prompt you to enter the details of your new repo. These should be mostly self-explanatory. The project slug is what will be used as the new folder name, as well as the name of the main .py file in the /src folder.

## Features 🏗️
The new project will be fairly minimal, but does include the following:
- Github actions CI incl. linting, formatting, import sorting and type checking 🔀
- Pre-commit config with hooks matching CI 🪝
- README.md with project title and description 📖
- .gitignore with standard files ignored 🚫
- /src folder with .py file matching project slug 📄
- /tests folder with template test as part of class matching project slug 🧪
- pyproject.toml with dependencies required for boilerplate 📐
- Config files for CI/pre-commit hook libraries and test coverage 🧩
