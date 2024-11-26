<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2024-11-26T18:16:36Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2pOlRnFzHuHicK3DzlO9SCGq22t",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2pOlRnFzHuHicK3DzlO9SCGq22t"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2pOlQNwC0Mrmjo3GxTdSXjPmlf9",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2pOlQNwC0Mrmjo3GxTdSXjPmlf9"
				},
				"enabled": true
			},
			"created_at": "2024-11-26T18:16:25Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2pOlQQqoZQ7k4A3psCQPmeyrWvA",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2pOlQQqoZQ7k4A3psCQPmeyrWvA"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
