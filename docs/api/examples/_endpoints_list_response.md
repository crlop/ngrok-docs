<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2024-11-26T18:16:28Z",
			"hostport": "afd33a9fad8d.ngrok.paid:443",
			"id": "ep_2pOlQkBIzEdbDiNp1YR8az5bB6i",
			"name": "command_line",
			"principal": {
				"id": "usr_2pOlOJUWfaxaH89CLVwTNs0Tng0",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://afd33a9fad8d.ngrok.paid",
			"tunnel": {
				"id": "tn_2pOlQkBIzEdbDiNp1YR8az5bB6i",
				"uri": "https://api.ngrok.com/tunnels/tn_2pOlQkBIzEdbDiNp1YR8az5bB6i"
			},
			"tunnel_session": {
				"id": "ts_2pOlQjNO1QvBfMU3mloDn9fhpP5",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2pOlQjNO1QvBfMU3mloDn9fhpP5"
			},
			"type": "ephemeral",
			"updated_at": "2024-11-26T18:16:28Z",
			"upstream_url": "http://localhost:80",
			"url": "https://afd33a9fad8d.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2024-11-26T18:16:26Z",
			"domain": {
				"id": "rd_2pOlQKxM7lVVn2NxvkrY7PMy4T0",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2pOlQKxM7lVVn2NxvkrY7PMy4T0"
			},
			"edge": {
				"id": "edgtls_2pOlQQqoZQ7k4A3psCQPmeyrWvA",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2pOlQQqoZQ7k4A3psCQPmeyrWvA"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2pOlQYKeaoGBuGuGbItEon6lbFc",
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2024-11-26T18:16:26Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
