# bughunt

Learn the basics of Go by fixing a simple program.

## Install Go

Download and install Go: http://golang.org/doc/install.

Setup your development environment: http://golang.org/doc/code.html.

## Setup the repo

Run `go get -d github.org/kvu787/pong`.

OR

Download and extract the repo to:

`$GOPATH/src/github.org/kvu787/pong`.

## Learn Go

### Bughunt!

Some nasty bugs are crawling around our repo! Follow the instructions below to squash them.

1. `cd "$GOPATH/src/github.org/kvu787/pong"`.
2. Run `go run bughunt/fixme.go`.
3. Edit `fixme.go` and use the compiler and runtime errors to squash those bugs. (See the `diff` file for hints.)
4. `while (bugs != null) { goto(2) }`.

### Interactive Go tutorial

See http://tour.golang.org/.

### More resources

- http://blog.golang.org/index
- http://www.golang-book.com/
- https://gobyexample.com/
