# py-script-searcher

An API that allows you to search for a python script inside the machine and execute it.
<br />
<br />

## Common Installation Errors

<br />

- Problem while installing requirements through pip

```
...

RuntimeError: cargo not found in PATH. Please install rust...

...
```

This normally occurs because the version of pip doesn't fully support wheels, upgrade pip to version 22+ and it should solve the problem.
