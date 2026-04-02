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
