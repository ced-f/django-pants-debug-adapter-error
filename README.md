# Demo project error using `./pants test --debug-adapter`

Run a test
`PANTS_SHA=32111b242c7248ec553926b78957a5ae5d259366 ./pants test helloworld/person/models_test.py`

Run a test using debug adapter
`PANTS_SHA=32111b242c7248ec553926b78957a5ae5d259366 ./pants test --debug-adapter helloworld/person/models_test.py`

Attaching via VSCode Debugger results in following error:

```
ModuleNotFoundError: No module named 'pex'
```

