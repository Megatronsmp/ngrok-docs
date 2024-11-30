<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2024-11-30T10:08:35Z",
			"hostport": "54e207beb10a.ngrok.paid:443",
			"id": "ep_2pZ6agkUUxTv1WpuHoE3tfyzg5T",
			"name": "command_line",
			"principal": {
				"id": "usr_2pZ6YFDDymVsoxyTMoJmi1j3iOo",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://54e207beb10a.ngrok.paid",
			"tunnel": {
				"id": "tn_2pZ6agkUUxTv1WpuHoE3tfyzg5T",
				"uri": "https://api.ngrok.com/tunnels/tn_2pZ6agkUUxTv1WpuHoE3tfyzg5T"
			},
			"tunnel_session": {
				"id": "ts_2pZ6alrsKHzlHDSHysfLfS9s3cl",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2pZ6alrsKHzlHDSHysfLfS9s3cl"
			},
			"type": "ephemeral",
			"updated_at": "2024-11-30T10:08:35Z",
			"upstream_url": "http://localhost:80",
			"url": "https://54e207beb10a.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2024-11-30T10:08:32Z",
			"domain": {
				"id": "rd_2pZ6aLQl9oG7O75BGBZVDhQB1Pq",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2pZ6aLQl9oG7O75BGBZVDhQB1Pq"
			},
			"edge": {
				"id": "edgtls_2pZ6aKrggP91ITPhFzE0hjgRNkN",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2pZ6aKrggP91ITPhFzE0hjgRNkN"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2pZ6aObFxPxFhrGdX8xrfZP8u0l",
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2024-11-30T10:08:32Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
