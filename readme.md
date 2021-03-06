[![Go Report](https://goreportcard.com/badge/github.com/goshco/arrays)](https://goreportcard.com/report/github.com/goshco/arrays)
[![License](https://img.shields.io/:license-mit-blue.svg?style=flat-square)](#license)
[![Say Thanks!](https://img.shields.io/badge/Say%20Thanks-!-1EAEDB.svg)](https://saythanks.io/to/iamalirezaj)

# Go arrays management
This package is provided to be used on golang and it gives clean methods to handle arrays.

# Requirement
* Golang 1.12.x: keep your compiler up to date :)
* reflect

**The package is in process.**

## Install
Run this commands

    $ go get github.com/MrJoshLab/go-collection

## Basic Usage
You must to import the package name 
```go
import (
    collection "github.com/MrJoshLab/go-collection"
)
```
You also need fmt package to print results in console
```go
import "fmt"
```

The following illustrates how you can use Array type or function to use methods.
```go
data := map[string] string { "say": "hello" }
c := collection.New(data)

// example:
fmt.Println(c.Has("say"))
// return true

fmt.Println(c.Get("say"))
// return "hello"
```

## License
The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
