# go-commands
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