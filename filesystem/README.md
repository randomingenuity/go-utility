[![GoDoc](https://godoc.org/github.com/RandomIngenuity/go-utility/filesystem?status.svg)](https://godoc.org/github.com/RandomIngenuity/go-utility/filesystem)
[![Build Status](https://travis-ci.org/RandomIngenuity/go-utility.svg?branch=master)](https://travis-ci.org/RandomIngenuity/go-utility)
[![Coverage Status](https://coveralls.io/repos/github/RandomIngenuity/go-utility/badge.svg?branch=master)](https://coveralls.io/github/RandomIngenuity/go-utility?branch=master)
[![Go Report Card](https://goreportcard.com/badge/github.com/RandomIngenuity/go-utility)](https://goreportcard.com/report/github.com/RandomIngenuity/go-utility)

# bounceback_reader

An `io.ReadSeeker` that returns to the right place before reading. Useful when the same file resource is being reused for reads or writes throughout that file.

# list_files

A recursive path walker that supports filters.

# seekable_buffer

A memory structure that satisfies `io.ReadWriteSeeker`.