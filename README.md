# sklearn-stubs

This installable package contains the `sklearn` type stubs copied from Microsoft's
[`python-type-stubs`](https://github.com/microsoft/python-type-stubs) repository.
It is packaged as `sklearn-stubs`, the stub-only package name for the import
package `sklearn`.

Source path:
[`stubs/sklearn`](https://github.com/microsoft/python-type-stubs/tree/main/stubs/sklearn)

Copied from upstream commit:
[`692c37c3969d22612b295ddf7e7af5907204a386`](https://github.com/microsoft/python-type-stubs/tree/692c37c3969d22612b295ddf7e7af5907204a386/stubs/sklearn)

## Installation

This package is intended to be installed directly from Git.

With uv:

```shell
uv add "sklearn-stubs @ git+https://github.com/juliancoffeelab/scikit-learn-stubs.git"
```

Or, for a development-only dependency:

```shell
uv add --dev "sklearn-stubs @ git+https://github.com/juliancoffeelab/scikit-learn-stubs.git"
```

With pip:

```shell
python -m pip install "sklearn-stubs @ git+https://github.com/juliancoffeelab/scikit-learn-stubs.git"
```

You can also pin a branch, tag, or commit:

```shell
uv add --dev "sklearn-stubs @ git+https://github.com/juliancoffeelab/scikit-learn-stubs.git@main"
python -m pip install "sklearn-stubs @ git+https://github.com/juliancoffeelab/scikit-learn-stubs.git@main"
```

## Type checker configuration

Install this package in the same Python environment where your type checker
runs. For normal virtualenv-based workflows, no extra configuration should be
needed: mypy, Pyright, Pylance, and other PEP 561-aware tools should discover
the installed `sklearn-stubs` package automatically.

For mypy, make sure you run mypy from the project environment:

```shell
uv run mypy .
```

For Pyright, use the same environment that contains the package, for example:

```shell
uv run pyright
```

You generally do not need `mypy_path`, `stubPath`, or custom search paths unless
you are deliberately keeping these stubs outside the environment that runs your
type checker.

## License and attribution

The copied stubs are licensed under the MIT License. Copyright belongs to
Microsoft Corporation and any other upstream contributors. The original MIT
license text is included in [`LICENSE`](LICENSE).

All credit for the copied stub files goes to Microsoft and the contributors to
`microsoft/python-type-stubs`. This repository is an extracted copy of the
`sklearn` stubs for convenience.

## See Also

- [`matplotlib-stubs`](https://github.com/juliancoffeelab/matplotlib-stubs)
