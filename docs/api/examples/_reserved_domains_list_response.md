<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"reserved_domains": [
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2pOlONtneerYCfPHf3wKQI1NwGj",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2pOlONtneerYCfPHf3wKQI1NwGj"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.24m7drdfwprhsjyug.local-ngrok-cname.com",
			"created_at": "2024-11-26T18:16:09Z",
			"domain": "myapp.mydomain.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2pOlOPVhVA5dkf6wBwNGAsi8ZTP",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2pOlOPVhVA5dkf6wBwNGAsi8ZTP"
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
					"started_at": "2024-11-26T18:16:09Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.24m7drdfwprhsjyug.local-ngrok-cname.com",
			"created_at": "2024-11-26T18:16:09Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2pOlOPjTmPzPZ9ixkPadNJCDgbu",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2pOlOPjTmPzPZ9ixkPadNJCDgbu"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
