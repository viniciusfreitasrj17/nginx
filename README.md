# Nginx

## API Gateway

### Access Service 1 by route with resourse

```sh
curl -X GET http://localhost/service1/test.html
```

### Access Service 1 by route

```sh
curl -X GET http://localhost/service1
```

### Access Service 2 by route

```sh
curl -X GET http://localhost/service2
```

### Access Service 1 by port

```sh
curl -X GET http://localhost:8081/
```

### Access Service 2 by port

```sh
curl -X GET http://localhost:8082/
```

## Load Balancer (service1 and service2)

```sh
curl -X GET http://localhost:8083/
```

## Fastcgi

```sh
curl -X GET http://localhost:8085/
```

## Cache and Performance

```sh
curl -X GET http://localhost:8086/
```

## HTTPS

```sh
curl -X GET https://localhost/
```
