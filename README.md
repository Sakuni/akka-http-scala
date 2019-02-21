# akka-http-scala

Run Server <br>
curl -XGET localhost:8080/hello in the terminal <br>
or http://localhost:8080/hello in the browser <br><br>
Run WebServer <br>
curl -H "Content-Type: application/json" -X POST -d '{"items":[{"name":"hhgtg","id":42}]}' http://localhost:8080/create-order <br>
to add an item and then <br>
curl -XGET localhost:8080/item/42 <br>
or http://localhost:8080/item/42 to view it.

