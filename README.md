# wizall-api-client-go

[![Go Reference](https://pkg.go.dev/badge/github.com/brokeyourbike/wizall-api-client-go.svg)](https://pkg.go.dev/github.com/brokeyourbike/wizall-api-client-go)
[![Go Report Card](https://goreportcard.com/badge/github.com/brokeyourbike/wizall-api-client-go)](https://goreportcard.com/report/github.com/brokeyourbike/wizall-api-client-go)
[![Maintainability](https://api.codeclimate.com/v1/badges/fc5997f243509e067be5/maintainability)](https://codeclimate.com/github/brokeyourbike/wizall-api-client-go/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/fc5997f243509e067be5/test_coverage)](https://codeclimate.com/github/brokeyourbike/wizall-api-client-go/test_coverage)

Wizall API client for Go

## Installation

```bash
go get github.com/brokeyourbike/wizall-api-client-go
```

## Usage

```go
client := wizall.NewClient("testagent-api.wizall.com", "client_id", "client_secret", "username", "password", "country")
client.Token(context.TODO())
```

## Authors
- [Ivan Stasiuk](https://github.com/brokeyourbike) | [Twitter](https://twitter.com/brokeyourbike) | [LinkedIn](https://www.linkedin.com/in/brokeyourbike) | [stasi.uk](https://stasi.uk)

## License
[BSD-3-Clause License](https://github.com/brokeyourbike/wizall-api-client-go/blob/main/LICENSE)
