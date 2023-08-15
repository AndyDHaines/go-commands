# Go-commands

[![Generic badge](https://img.shields.io/badge/go-1.21.0-<COLOR>.svg)](https://shields.io/) [![GitHub license](https://badgen.net/github/license/Naereen/Strapdown.js)](https://github.com/Naereen/StrapDown.js/blob/master/LICENSE) [![GitHub branches](https://badgen.net/github/branches/Naereen/Strapdown.js)](https://github.com/Naereen/Strapdown.js/) [![GitHub latest commit](https://badgen.net/github/last-commit/Naereen/Strapdown.js)](https://GitHub.com/Naereen/StrapDown.js/commit/)

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