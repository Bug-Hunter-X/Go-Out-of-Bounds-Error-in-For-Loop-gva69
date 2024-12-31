# Go Out of Bounds Error in For Loop

This example demonstrates a common out-of-bounds error in Go when iterating over arrays or slices.

The `bug.go` file contains a function `myFunc` that attempts to iterate over a slice using a loop condition `i <= len(a)`. This condition leads to an index out of bounds error because the index `i` will eventually reach the length of the slice, which is an invalid index.

The `bugSolution.go` file provides a corrected version of the function, using the correct condition `i < len(a)` to avoid the error.
