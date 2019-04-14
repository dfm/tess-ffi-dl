Download the TESS FFI files from MAST.

## Dependencies

This is a Python package so you'll need Python (tested on v3.6) and the following dependancies:

- [tqdm](https://tqdm.github.io)
- [requests](http://docs.python-requests.org)
- [astropy](https://www.astropy.org)

## Usage

To download all the FFIs for Sector 4 to the directory `data`:

```bash
tess-ffi-dl data 4
```

You can also specify a camera and chip number as follows:

```bash
tess-ffi-dl data 4 --camera=4 --chip=2
```
