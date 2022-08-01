---
title: Introduction

---
<!--Introduction-->

One of Go’s biggest strengths is concurrency. This is the ability of functions to run independently of each other. In Go, functions that run concurrently are called Goroutines.

In other words, a goroutine is a lightweight thread managed by the Go runtime. A thread is a lightweight process, a unit which executes the code under a program.

We create goroutines using the `go` statement. See the syntax below:

```go
go myFunction()
```

Let’s take this a step further and define channels.

Go also provides communication mechanisms called channels that we shall explore in the next scenario.

Next, we’ll discuss goroutines.