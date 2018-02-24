![alt tag](https://upload.wikimedia.org/wikipedia/commons/2/23/Golang.png)

[![Build Status](https://travis-ci.org/ShubhamBansal1997/go-api-starter-kit.svg?branch=master)](https://travis-ci.org/ShubhamBansal1997/go-api-starter-kit)


Welcome to **Go API Starter KIT**!

The fastest way to deploy a restful api's with [Gin Framework](https://gin-gonic.github.io/gin/) with a structured project that defaults to **PostgreSQL** database and **Redis** as the session storage.

## Configured with

* [go-gorp](https://github.com/go-gorp/gorp): Go Relational Persistence
* [RedisStore](https://github.com/gin-gonic/contrib/tree/master/sessions): Gin middleware for session management with multi-backend support (currently cookie, Redis).
* Built-in **CORS Middleware**
* Feature **PostgreSQL 9.6** JSON queries
* Unit test

### Installation

```
$ go get github.com/ShubhamBansal1997/go-api-starter-kit
```

```
$ cd $GOPATH/src/github.com/ShubhamBansal1997/go-api-starter-kit
```

```
$ go get -t -v ./...
```

> Sometimes you need to get this package manually
```
$ go get github.com/bmizerany/assert
```

You will find the **database.sql** in `db/database.sql`

And you can import the postgres database using this command:
```
$ psql -U postgres -h localhost < ./db/database.sql
```

## Running Your Application

```
$ go run *.go
```

## Building Your Application

```
$ go build -v
```

```
$ ./gin-boilerplate
```

## Testing Your Application

```
$ go test -v ./tests/*
```


## License
(The MIT License)
