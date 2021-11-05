# vamp-cloud-demo-circleci

Webhook payload for the onFailure webhook to trigger the CircleCI pipeline
```
{
	"branch": "main",
	"parameters": {
		"delete": true,
		"version": "%%TARGET_SERVICE_VERSION%%",
		"kubernetes_namespace": "%%NAMESPACE%%"
	}
}
