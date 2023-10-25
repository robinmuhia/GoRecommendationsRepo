# Awesome Golang Repository to learn Golang [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

> A curated list of libraries, tools, blog articles, videos and books to help any willing individual to learn Golang.

## Contents

- [Hello World](#helloworld)
- [Conventions](#conventions)
- [APIs](#APIs)
- [Databases](#databases)
- [Testing](#testing)
- [Libraries](#libraries)

## Hello World

### Install

[Linux](https://www.digitalocean.com/community/tutorials/how-to-install-go-on-ubuntu-20-04)
[Windows](https://www.golinuxcloud.com/install-golang-on-windows/)
[MacOS](https://jimkang.medium.com/install-go-on-mac-with-homebrew-5fa421fc55f5)

### Basics

- You can always purchase an udemy course. I recommend [Akhil Sharma](https://www.udemy.com/course/build-3-simple-golang-projects/). He also has a very brilliant youtube channel that covers various Golang projects. Find his youtube channel [here](https://www.youtube.com/channel/UCgMjDy6Y7WISZ529S4VyXUg)
- If you're a visual learner, I recommend this video on [Freecodecamp's youtube](https://youtu.be/un6ZyFkqFKo?si=dR-ahY9Gm-rZzwby)
- If you're in need of a platform, I recommend the Boot.dev golang course to get a grasp of the language. The link for the course is [here](https://www.boot.dev/assignments/224252be-adc9-452f-8ed0-0b305b25d0cb)

### Tools

- For Visual Studio Code users, make sure to install the Go extension. It is a lifesaver.

## Conventions

### Talks

- Watch/listen to this [talk](https://www.youtube.com/watch?v=gi7t6Pl9rxE&t=6934s) to get the nuances of the language

### Books

- Read the following books:
- If you send me a screenshot of you contributing/donating a dollar to any open-source repo, i will try to send you an epub of the books:

[100 Go Mistakes and How to Avoid Them](https://www.manning.com/books/100-go-mistakes-and-how-to-avoid-them)
[Learning Go, 2nd Edition](https://www.oreilly.com/library/view/learning-go-2nd/9781098139285)

``

## APIS

## Frameworks

- I recommend using the in-built http module and a router, either [Gorilla Mux](https://github.com/gorilla/mux) or [Chi](https://github.com/go-chi/chi)

- A major framework I recommend is [Gin Gonic](https://gin-gonic.com/)

### REST

- To learn about REST architecture in Go, read [Building RESTful Web services with Go](https://www.packtpub.com/product/building-restful-web-services-with-go/9781788294287)

### GraphQL

- To use graphql, try [99designs' gqlgen](https://github.com/99designs/gqlgen)

### Remote Procedure Calls

- I recommend using gRPC by [Google](https://github.com/grpc/grpc-go)

## Databases

### SQL

- You can use [goose](https://github.com/pressly/goose) for database migrations

- You can write raw sql queries that will be generated into type-safe code using [Kyle's sqlc package here](https://github.com/sqlc-dev/sqlc)

### ORMS

- You can use [Gorm]()https://github.com/go-gorm/gorm as your ORM

### NOSQL

- MongoDB, use [this](https://github.com/mongodb/mongo-go-driver)
- DynamoDB, use [this](https://github.com/aws/aws-sdk-go-v2)

## Testing

- Use Golang's inbuilt testing module to run tests in go. Read [this](https://blog.jetbrains.com/go/2022/11/22/comprehensive-guide-to-testing-in-go/) to better understand testing in go.

## Libraries

This is a list of various Golang libraries to use in projects.

- [Sentry for error handling](https://github.com/getsentry/sentry-go)
- [Generate UUID](https://github.com/google/uuid)
- [Validators for strings,structs etc](https://github.com/asaskevich/govalidator)
- [For creating mocks for testing](https://github.com/brianvoe/gofakeit)
