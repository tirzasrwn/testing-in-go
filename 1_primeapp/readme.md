# primeapp

## Run

```sh
go test .
```

## Test Coverage

```sh
go test -cover .

go test -coverprofile=coverage.out
go tool cover -html=coverage.out -o ./coverage.html
open ./coverage.html
```
