# rem-testfiles

A series of folders that can be used to run the tests for the Rusty-Extraction-Maestro (REM) toolchain.

Instead of:

```bash
cargo run test src_tests
```

The following can be run:

```bash
cargo run test-github https://github.com/RuleBrittonica/rem-testfiles
```

This provides more flexibility and makes it easier to contribute to the overall project if that becomes an option

## Project Structure

### borrower

* input
* method_call_mut
* output
* pre_extract

### controller

* input
* output

### repairer

* input
* output
