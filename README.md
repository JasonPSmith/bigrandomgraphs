# bigrandomgraphs

Fast, parallel generation of large sparse random graphs in C++ with a Python interface.

## Install

```bash
pip install bigrandomgraphs          # from PyPI (once published)
pip install .                        # from a local checkout
pip install git+https://github.com/<user>/bigrandomgraphs.git
```

Python ≥ 3.9. Source installs need a C++ compiler; CMake ≥ 3.15 is fetched automatically by the build frontend if not already present. Pre-built wheels are produced by CI for Linux x86_64, macOS arm64, macOS x86_64, and Windows x64 across CPython 3.9–3.13.

## TODO

* [ ] Add "Publish to PyPI" in github workflows

## License

See [LICENSE](LICENSE).
