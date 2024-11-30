<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"reserved_domains": [
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2pZ6YLpDc24YSaptcBUV8FRWLCd",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2pZ6YLpDc24YSaptcBUV8FRWLCd"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.2hj3wxcip5wralu25.local-ngrok-cname.com",
			"created_at": "2024-11-30T10:08:16Z",
			"domain": "myapp.mydomain.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2pZ6YN61Bh4eUX4DI23BCBv0WCD",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2pZ6YN61Bh4eUX4DI23BCBv0WCD"
		},
		{
			"acme_challenge_cname_target": null,
			"certificate": null,
			"certificate_management_policy": {
				"authority": "letsencrypt",
				"private_key_type": "ecdsa"
			},
			"certificate_management_status": {
				"provisioning_job": {
					"error_code": null,
					"msg": "Managed certificate provisioning in progress.",
					"retries_at": null,
					"started_at": "2024-11-30T10:08:16Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.2hj3wxcip5wralu25.local-ngrok-cname.com",
			"created_at": "2024-11-30T10:08:16Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2pZ6YLvza1SPzo2yduopySpJtDl",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2pZ6YLvza1SPzo2yduopySpJtDl"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
