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

- [Database access optimization](https://docs.djangoproject.com/en/dev/topics/db/optimization/) - Outlines the steps to take when attempting to optimize your database usage.
- [Django Performance Improvements - Part 1: Database Optimizations](https://blog.sentry.io/django-performance-improvements-part-1-database-optimizations/)
- [Automating Performance Testing in Django](https://testdriven.io/blog/django-performance-testing/)
- [Performing raw SQL queries](https://docs.djangoproject.com/en/dev/topics/db/sql/#performing-raw-sql-queries)

## Caching

### Tools

- [django-cacheback](https://github.com/codeinthehole/django-cacheback) - Smart caching for Django using Celery to refresh cached items asynchronously.
- [django-memoize](https://github.com/tdr-autosync/mi-lib-django_memoize) - A cache for function or method results.
- [django_model_cached_property](https://github.com/Legotckoi/django_model_cached_property) - Useful for caching of property results for more time than lifetime of object during the request.
- [django-cacheops](https://github.com/Suor/django-cacheops) - A slick ORM cache with automatic granular event-driven invalidation.
- [django-cachalot](https://github.com/noripyt/django-cachalot) - Caches your Django ORM queries and automatically invalidates them.
- [django-cache-machine](https://github.com/django-cache-machine/django-cache-machine) - Automatic caching and invalidation for Django models through the ORM.
- [django-request-cache](https://github.com/anexia/django-request-cache) - A Django app that provides a new cache on every request object. The cache is only kept within the request/response cycle.
- [django-ormcache](https://github.com/educreations/django-ormcache) - A cache manager mixin that provides some caching of objects for the ORM.
- [Varnish Cache](https://varnish-cache.org/intro/index.html#intro) - A web application accelerator also known as a caching HTTP reverse proxy.
- [PolyScale.ai](https://www.polyscale.ai/) - A high performance Data Delivery Network (DDN) that accelerates databases. Using smart caching, it improves query performance, lowers latency and makes data access and scale engineering a breeze, both on premise and at the edge.

### Articles

- [Django's cache framework](https://docs.djangoproject.com/en/dev/topics/cache/)
- [Varnish - 12 Days of Performance](https://www.revsys.com/12days/varnish/)

## Serialization

### Tools

- [drf_orjson_renderer](https://github.com/brianjbuck/drf_orjson_renderer) - A JSON renderer and parser for Django Rest Framework using the orjson library. Backed by Rust, orjson is safe, correct and fast.
- [Django Compression Middleware](https://github.com/friedelwolff/django-compression-middleware) - Django middleware to compress responses using algorithms such as Zstandard, Brotli, and gzip.
- [serpy](https://github.com/clarkduvall/serpy) - A super simple object serialization framework built for speed.
- [django-rest-marshmallow](https://github.com/marshmallow-code/django-rest-marshmallow) - Marshmallow schemas for Django REST framework.
- [marshmallow](https://github.com/marshmallow-code/marshmallow) - An ORM/ODM/framework-agnostic library for converting complex datatypes, such as objects, to and from native Python datatypes.

### Articles

- [Improve Serialization Performance in Django Rest Framework](https://hakibenita.com/django-rest-framework-slow) - How we reduced serialization time by 99%!
- [Python Serialization Benchmark](https://voidfiles.github.io/python-serialization-benchmark/) - A set of benchmarks for Python serialization frameworks.

## Tasks

### Tools

- [Celery](https://github.com/celery/celery) - Distributed Task Queue.
- [Celery Flower](https://github.com/mher/flower) - Real-time monitor and web admin for Celery distributed task queue.
- [django_dramatiq](https://github.com/Bogdanp/django_dramatiq) - A Django app that integrates with Dramatiq.
- [Django-RQ](https://github.com/rq/django-rq) - A simple app that provides django integration for RQ (Redis Queue).
- [Django Q](https://github.com/Koed00/django-q) - A multiprocessing distributed task queue for Django.

### Articles

- [Improving Scalability, Reliability, and Efficiency of a Python Service with Gevent](https://doordash.engineering/2021/01/19/scaling-efficienc-of-a-python-service-with-gevent/)

## Servers

### Tools

- [gevents](https://www.gevent.org/) - A coroutine-based Python networking library that uses greenlet to provide a high-level synchronous API on top of the libev or libuv event loop.

### Articles

- [Is Django too slow?](https://mattsegal.dev/is-django-too-slow.html)
- [Gunicorn Async Workers with gevent](https://www.joelsleppy.com/blog/gunicorn-async-workers-with-gevent/)

## Testing

- Use Golang's inbuilt testing module to run tests in go. Read [this](https://blog.jetbrains.com/go/2022/11/22/comprehensive-guide-to-testing-in-go/) to better understand testing in go.

## Libraries

This is a list of various Golang libraries to use in projects.

- [Sentry for error handling](https://github.com/getsentry/sentry-go)
- [Generate UUID](https://github.com/google/uuid)
- [Validators for strings,structs etc](https://github.com/asaskevich/govalidator)
- [For creating mocks for testing](https://github.com/brianvoe/gofakeit)
