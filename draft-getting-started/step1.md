# Start Kubernetes

First, you will need to start your Kubernetes cluster:

`launch.sh`{{execute}}

# Install Helm

Draft uses Helm under the covers in order to generate deployable packages. Let's install Helm:

`curl -O https://storage.googleapis.com/kubernetes-helm/helm-v2.13.0-linux-amd64.tar.gz ; tar xvzf helm-v2.13.0-linux-amd64.tar.gz ; mv linux-amd64/helm /usr/local/bin`{{execute}}

And initialize it:

`helm init`{{execute}}

# Install Draft

Now that Helm is installed and configured, you can install Draft:

`curl -O https://azuredraft.blob.core.windows.net/draft/draft-v0.16.0-linux-amd64.tar.gz ; tar xvzf draft-v0.16.0-linux-amd64.tar.gz ; mv linux-amd64/draft /usr/local/bin`{{execute}}

And initialize it:

`draft init`{{execute}}
