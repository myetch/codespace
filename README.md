# APC C++ Codespace Template

Cookiecutter template for C++23 projects with a Dev Container (clang 22, CMake, Ninja, LLDB, clangd)
and experimental `import std;` support.

## Usage

```sh
uvx cookiecutter gh:<your-github-user>/<this-repo>
```

or `pip install cookiecutter` and run `cookiecutter gh:<your-github-user>/<this-repo>`.

You will be asked for `project_name`, which is used as the folder name and the CMake target / executable name,
so use a name without spaces (e.g. `Homework1`).
