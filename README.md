# Go-commands

[![Generic badge](https://img.shields.io/badge/go-1.21.0-<COLOR>.svg)](https://shields.io/) 
[![GitHub license](https://badgen.net/github/license/AndyDHaines/go-commands)](https://github.com/AndyDHaines/go-commands/blob/main/LICENSE) 
[![GitHub branches](https://badgen.net/github/branches/AndyDHaines/go-commands)](https://github.com/AndyDHaines/go-commands/) 
[![GitHub latest commit](https://badgen.net/github/last-commit/AndyDHaines/go-commands)](https://github.com/AndyDHaines/go-commands/commits/)

Useful Go commands that can be run in the terminal

## Go Testing

This command will show you the percentage of code coverage
```
go test -cover
```
Generating a coverage profile
```
go test -coverprofile=coverage.out
```
Viewing the coverage profile
```
go tool cover -html=coverage.out
```

## Go Vulnerabilities 

Command-line tool that helps Go users find known vulnerabilities in their project dependencies. The tool can analyze both codebases and binaries, and it reduces noise by prioritizing vulnerabilities in functions that your code is actually calling.

You can install the latest version of govulncheck with this command
```
go install golang.org/x/vuln/cmd/govulncheck@latest
```

Run govulncheck inside your module
```
govulncheck ./...
```
