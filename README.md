# wizall-api-client-go
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