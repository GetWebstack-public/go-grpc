# go-grpc

A gRPC service example built with [gRPC-Go](https://grpc.io/docs/languages/go/) — a high-performance, open source RPC framework using Protocol Buffers for service definition and serialization.

## Run with gws

### 1. Install the GetWebstack CLI

Install the [GetWebstack](https://getwebstack.com) CLI ([docs](https://getwebstack.com/docs) | [installation](https://getwebstack.com/docs/installation)):

```bash
curl -sSL https://getwebstack.com/install.sh | bash
```

### 2. Clone the repository

```bash
git clone https://github.com/GetWebstack-public/go-grpc
cd go-grpc
```

### 3. Initialise from template setup

```bash
gws init --from-file gws.json
```

### 4. Deploy the service

```bash
gws up
```

### 5. Stream logs

```bash
gws logs
```

### 6. See deployment status

```bash
gws status
```

## Other Go projects

| Project | Framework | Description |
|---|---|---|
| [go-chi](https://github.com/GetWebstack-public/go-chi) | [Chi](https://go-chi.io/) | Lightweight, idiomatic router for Go HTTP services |
| [go-echo](https://github.com/GetWebstack-public/go-echo) | [Echo](https://echo.labstack.com/) | High performance, minimalist Go web framework |
| [go-fiber](https://github.com/GetWebstack-public/go-fiber) | [Fiber](https://gofiber.io/) | Express-inspired web framework built on Fasthttp |
| [go-generic](https://github.com/GetWebstack-public/go-generic) | — | Go generics example |
| [go-gin](https://github.com/GetWebstack-public/go-gin) | [Gin](https://gin-gonic.com/) | Fast HTTP web framework for Go |
| [hugo](https://github.com/GetWebstack-public/hugo) | [Hugo](https://gohugo.io/) | Static site generator written in Go |

## Other project families

| Family | Repository | Description |
|---|---|---|
| Python | [python-projects](https://github.com/GetWebstack-public/python-projects) | FastAPI, Django, Flask, and more |
| JS/TS Backend | [js-ts-backend](https://github.com/GetWebstack-public/js-ts-backend) | Express, NestJS, Fastify, and more |
| JS/TS Frontend | [js-ts-frontend](https://github.com/GetWebstack-public/js-ts-frontend) | React, Next.js, Vue, and more |
| Multirepo | [react-express-mono-repo](https://github.com/GetWebstack-public/react-express-mono-repo) | React + Express multi-service workspace |
