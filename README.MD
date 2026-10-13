# ESEP Grade Calculator

This library is a simple utility to calculate your grades.

## Runtime requirements:
Golang 1.24+

## Project Files

- `grade_calculator.go` - contains the grade calculator logic
- `grade_calculator_test.go` - contains the unit tests
- `go.mod` - contains the Go module configuration

Run unit tests:
```
cd grade_calculator/
go test ./...
```

Run unit tests with code coverage:
```
cd grade_calculator/
go test -coverprofile=coverage.txt ./...
```

To view the the total coverage
```
go tool cover -func=coverage.txt
```

To view the total coverage report in a browser
```
go tool cover -html=coverage.txt
```