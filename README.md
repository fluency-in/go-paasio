# Go: Paasio

Write a program that reports network IO statistics

You are writing a [PaaS][], and you need a way to bill customers based
on network and filesystem usage.

Create a wrapper for network connections and files that can report IO
statistics. The wrapper must report:

- The total number of bytes read/written.
- The total number of read/write operations.

[PaaS]: http://en.wikipedia.org/wiki/Platform_as_a_service

The tests are written using the `testing` package in the standard library.

To run a test file use the `go test` command:

    go test

## Source

Brian Matsuo [https://github.com/bmatsuo](https://github.com/bmatsuo)

This exercise is from the [Go][go] track on [Exercism][exercism]

[exercism]: http://exercism.io
[go]: http://exercism.io/languages/go



