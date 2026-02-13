# Post Quantum VPN

## Overview

## Getting Started

### Building the project
```
make run-client # Builds and runs the client
make run-server # Builds and runs the server
make help # Outputs all available make commands in the makefile
```

## Tests
### Writing Tests
1. Create a cpp file for the module you want to test in tests/
2. Add your test code to the newly created file
3. Declare the function in tests/tests.h
4. Add Run(TestFunction); in tests/test_runner.cpp

See the sample tests included for reference.

### Running Tests
```
make test # Builds all tests
make run-test # Build the tests and runs all tests
```

## Authors
 - Chris Manlove
 - Cameron Rosenthal
 - Hunter Tran
 - Quan Truong


