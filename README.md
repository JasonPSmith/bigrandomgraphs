# bigrandomgraphs

Fast, parallel generation of large sparse random graphs in C++ with a Python interface.

## Install

```bash
pip install bigrandomgraphs          # from PyPI (once published)
pip install .                        # from a local checkout
pip install git+https://github.com/<user>/bigrandomgraphs.git
```

Python ≥ 3.9. Source installs need a C++ compiler; CMake ≥ 3.15 is fetched automatically by the build frontend if not already present. Pre-built wheels are produced by CI for Linux x86_64, macOS arm64, macOS x86_64, and Windows x64 across CPython 3.9–3.13.

## Testing

```bash
pip install -e .[test]
python -m pytest
```

Use `python -m pytest` rather than bare `pytest` — the latter resolves via `$PATH` and can end up in a Python environment that doesn't have `bigrandomgraphs` installed, producing a confusing `ModuleNotFoundError: No module named 'pybrg'` at collection time.

## TODO

* [ ] Add "Publish to PyPI" in github workflows

## License

See [LICENSE](LICENSE).
