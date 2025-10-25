# Go + GraphQL + Relay

Run the ```main.go``` file
```
go run main.go
```

The GraphQL server will now be running at http://localhost:8080/graphql

To test it, run the following curl command on your terminal:
```
curl -XPOST http://localhost:8080/graphql \
-H 'Content-Type: application/graphql' \
-d 'query Root{ latestPost }'
```