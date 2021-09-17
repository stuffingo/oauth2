# OAuth2 for Go

oauth2 package contains a client implementation for OAuth 2.0 spec.

This is a fork of [golang.org/x/oauth2](https://golang.org/x/oauth2).


## Installation

~~~~
go get github.com/stuffingo/oauth2
~~~~

Or you can manually git clone the repository to
`$(go env GOPATH)/src/github.com/stuffingo/oauth2`.

See pkg.go.dev for further documentation and examples.

* [pkg.go.dev/github.com/stuffingo/oauth2](https://pkg.go.dev/github.com/stuffingo/oauth2)
* [pkg.go.dev/github.com/stuffingo/oauth2/google](https://pkg.go.dev/github.com/stuffingo/oauth2/google)

## Policy for new packages

We no longer accept new provider-specific packages in this repo if all
they do is add a single endpoint variable. If you just want to add a
single endpoint, add it to the
[pkg.go.dev/github.com/stuffingo/oauth2/endpoints](https://pkg.go.dev/github.com/stuffingo/oauth2/endpoints)
package.

## Report Issues / Send Patches

This repository uses Gerrit for code changes. To learn how to submit changes to
this repository, see https://golang.org/doc/contribute.html.

The main issue tracker for the oauth2 repository is located at
https://github.com/golang/oauth2/issues.
