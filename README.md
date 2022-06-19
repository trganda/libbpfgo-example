# libbpfgo-example

A Example of libbpfgo, fixed the [issues](https://github.com/grantseltzer/libbpfgo-example/issues/4) while using `go > 1.3`

Check out selftests in libbpfgo for more (and more up-to-date) examples: [here](https://github.com/aquasecurity/libbpfgo/tree/main/selftest)

This is an example of writing a small program with [libbpfgo](https://github.com/aquasecurity/tracee/tree/main/libbpfgo), a Go wrapper for libbpf.

To build simply run `make` and run the resulting `libbpfgo-prog` binary.

> In `main.go`, i have change the kprobe to __arm64_sys_execve because my machine was arm based. You can change it on yourself.
