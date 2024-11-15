<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"event_subscriptions": [
		{
			"created_at": "2024-11-15T17:26:26Z",
			"description": "ip policy creations",
			"destinations": [
				{
					"id": "ed_2otazJDoRL7RVQPMEBtEw0VI725",
					"uri": "https://api.ngrok.com/event_destinations/ed_2otazJDoRL7RVQPMEBtEw0VI725"
				}
			],
			"id": "esb_2otazJM5hqIr7TCxbfKPxP5H7Ac",
			"metadata": "{\"environment\": \"staging\"}",
			"sources": [
				{
					"type": "ip_policy_created.v0",
					"uri": "https://api.ngrok.com/event_subscriptions/esb_2otazJM5hqIr7TCxbfKPxP5H7Ac/sources/ip_policy_created.v0"
				}
			],
			"uri": "https://api.ngrok.com/event_subscriptions/esb_2otazJM5hqIr7TCxbfKPxP5H7Ac"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/event_subscriptions"
}
```