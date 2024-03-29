# Changelog

## [v1.1.0] - 2024-03-03

This release adds two new functions to the devices module.

### Added

- `list_owned_devices()` - returns a users owned devices in Entra ID ([`38ac9e1`](https://github.com/fedamerd/msgraph-py/commit/38ac9e1))
- `get_laps_password()` - returns the decoded LAPS password for a device ([`05943a8`](https://github.com/fedamerd/msgraph-py/commit/05943a8))
- Project URLs to `pyproject.toml` ([`cc8ac00`](https://github.com/fedamerd/msgraph-py/commit/cc8ac00))

### Changed

- List of functions in `README.md` now links to the corresponding Python modules ([`b5e158a`](https://github.com/fedamerd/msgraph-py/commit/b5e158a))

### Fixed

- Wrong return type hint in `list_group_members()` ([`0a95c48`](https://github.com/fedamerd/msgraph-py/commit/0a95c48))

## [v1.0.0] - 2024-02-21

First public release of **`msgraph-py`** – a Python package providing API wrappers to simplify interaction with Microsoft Graph API.

### Features

- Automatic caching and renewal of access tokens, avoiding unnecessary API-calls.
- Sets the correct headers and parameters for you when required (advanced queries).
- Pages results automatically when retrieving large datasets.
- Useful logging and error messages with the Python logging module.
- Optional integration with Django settings.py for reading environment variables.

### Installation

Releases are also published to [PyPI](https://pypi.org/project/msgraph-py/) and can be installed with the following command:

```console
python -m pip install msgraph-py
```

See the [README](https://github.com/fedamerd/msgraph-py/blob/main/README.md) for more information on how to get started, as well as usage examples.

### Contribute

Found a bug or want to request a feature? Open a new issue using the [issue tracker](https://github.com/fedamerd/msgraph-py/issues).

[v1.1.0]: https://github.com/fedamerd/msgraph-py/releases/tag/v1.1.0
[v1.0.0]: https://github.com/fedamerd/msgraph-py/releases/tag/v1.0.0
