# Ruby method_missing Bug

This example demonstrates a potential issue with Ruby's `method_missing` feature. The code uses `method_missing` to handle calls to methods that don't exist. While this can be convenient for dynamic method handling, it may lead to unexpected behavior if not properly implemented.  Specifically, errors caused by typos or incorrect method calls might be silently handled by `method_missing`, masking the actual problem.

The solution demonstrates a more robust approach to handling `method_missing`, providing better error handling and preventing accidental masking of true errors.
