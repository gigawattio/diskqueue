# diskqueue

[![Documentation](https://godoc.org/github.com/gigawattio/diskqueue?status.svg)](https://godoc.org/github.com/gigawattio/diskqueue)
[![Build Status](https://travis-ci.org/gigawattio/diskqueue.svg?branch=master)](https://travis-ci.org/gigawattio/diskqueue)
[![Report Card](https://goreportcard.com/badge/github.com/gigawattio/diskqueue)](https://goreportcard.com/report/github.com/gigawattio/diskqueue)

### About

Go (golang) package which provides a disk-backed queueing system.

Initial implementation lifted from NSQ, see https://github.com/nsqio/nsq/

and https://github.com/nsqio/nsq/blob/master/nsqd/diskqueue.go.

This package is used by [Gigawatt](http://gigawatt.io/).

### Requirements

* Go version 1.3 or newer

### Running the test suite

    go test ./...

#### License

Permissive MIT license, see the [LICENSE](LICENSE) file for more information.
