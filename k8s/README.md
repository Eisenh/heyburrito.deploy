# Deploying Hey Burrito on Kubernetes

1. Get an API key from the Slack developer console. 

2. Replace {API_KEY_HERE} with your API key in `yaml/heyburrito-deployment.yaml`.

3. Run `kubectl apply -f yaml/`.

TODO: Use a secret to store the API key and pass it into the container.
TODO: Add an Ingress resource with TLS.