## Layered Architecture Direcotry Structure Sample

Sample Directory structure for WebAPI.
like DDD,But Stricty speaking,not DDD :p
represents a layered architecture such as the figure below.

```
.
├── README.md
├── doc
├── src
│  ├── app
│  │  ├── application
│  │  │  ├── controller
│  │  │  ├── request
│  │  │  ├── response
│  │  │  └── usecase
│  │  ├── domain
│  │  │  ├── entity
│  │  │  ├── irepository
│  │  │  └── service
│  │  └── infra
│  │      └── repository_impl
│  ├── config
│  ├── framework
│  │  ├── database
│  │  ├── handler
│  │  ├── log
│  │  ├── middleware
│  │  └── router
│  ├── main.go
│  └── routes
├── tool
└── vendor
```
