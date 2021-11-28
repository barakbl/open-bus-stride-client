# open-bus-stride-client

Python client library to interact with the [Stride REST API](https://open-bus-stride-api.hasadna.org.il/docs)

## Usage

Refer to the [API Docs](https://open-bus-stride-api.hasadna.org.il/docs) for the available paths, parameter types and general usage.

The client provides the following methods:

* `stride.get(path, params=None)`: Make a GET request to the given path with optional params dict
* `stride.iterate(path, params=None, limit=1000)`: For list operations - iterate over all items up to the given limit.

See the [Jupyter notebooks](notebooks) for examples.

### Using the interactive Jupyter notebooks

For a very quickstart without any installation, use [our Jupyter notebooks online](https://mybinder.org/v2/gh/hasadna/open-bus-stride-client/HEAD?labpath=notebooks)

Browse the available notebooks in the file browser on the left sidebar.

### Using locally

Install the library

```
pip install --upgrade open-bus-stride-client
```
