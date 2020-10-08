# Example S3 webhook server for MCS

## Building
```
go build
```

You'll get the binary named `hookserver`.

## Running

```
./hookserver
```

It will listen for HTTP requests on TCP port 33345. It assumes https forwarding from nginx.

## Testing

To test signature correctness:
```
go test
```
