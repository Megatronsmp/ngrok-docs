<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2024-11-30T10:08:44Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2pZ6bqb43o1Xap11gLj2feXsu39",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2pZ6bqb43o1Xap11gLj2feXsu39"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2pZ6aOH5EBOaobCpdcOtqBmRAVg",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2pZ6aOH5EBOaobCpdcOtqBmRAVg"
				},
				"enabled": true
			},
			"created_at": "2024-11-30T10:08:32Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2pZ6aKrggP91ITPhFzE0hjgRNkN",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2pZ6aKrggP91ITPhFzE0hjgRNkN"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
