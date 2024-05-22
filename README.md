# FastCDC-Go

[![Docs](https://godoc.org/github.com/jotfs/fastcdc-go?status.svg)](https://pkg.go.dev/github.com/jotfs/fastcdc-go?tab=doc) [![Build Status](https://travis-ci.org/jotfs/fastcdc-go.svg?branch=master)](https://travis-ci.org/jotfs/fastcdc-go) [![codecov](https://codecov.io/gh/jotfs/fastcdc-go/branch/master/graph/badge.svg)](https://codecov.io/gh/jotfs/fastcdc-go) [![Go Report Card](https://goreportcard.com/badge/github.com/jotfs/fastcdc-go)](https://goreportcard.com/report/github.com/jotfs/fastcdc-go)

FastCDC-Go is a Go library implementing the [FastCDC](#references) content-defined chunking algorithm.

## Note
- this library is forked from "github.com/jotfs/fastcdc-go", with only 1 minor change: adding NewChunkerWithBuf method for reducing the gc stress
