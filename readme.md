# golang-healthchecker [![Healthchecker Pipeline](https://github.com/kkamara/golang-healthchecker/actions/workflows/ci.yml/badge.svg)](https://github.com/kkamara/golang-healthchecker/actions/workflows/ci.yml)

(22-Nov-2023) go run . --domain pexels.com

## Requirements

* [Go](https://www.golang.org).

## Usage

```bash
go run . --domain pexels.com
> [UP] pexels.com is reachable
> From: 192.168.1.232:51061
> To: 104.16.235.10:80
```

```bash
go run . -d pexels.com -p 80
> [UP] pexels.com is reachable
> From: 192.168.1.231:51062
> To: 104.16.235.10:80
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[BSD](https://opensource.org/licenses/BSD-3-Clause)
