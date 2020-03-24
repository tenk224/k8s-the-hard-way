# Kubernetes the hard way
## Disclaimer
- For learning kubernetes purpose, I use this [repo](https://github.com/kelseyhightower/kubernetes-the-hard-way) as a reference.
- This will be deployed to Google Cloud Platform (GCP).
- Some links in this repository might get outdated, please refer to the given link for the up-to-date one.
## Prerequisites
### Homebrew
Install Homebrew with [this](https://brew.sh/)
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```
Try to install wget with the following
```
brew install wget
```
### Google Cloud Platform SDK
Use the [tutorial](https://cloud.google.com/sdk/docs/downloads-versioned-archives) to install the SDK
```
wget https://dl.google.com/dl/cloudsdk/channels/rapid/downloads/google-cloud-sdk-285.0.1-darwin-x86_64.tar.gz
tar -xzvf google-cloud-sdk-285.0.1-darwin-x86_64.tar.gz
./install.sh
```
Or brew
```
brew install google-cloud-sdk
```
Check installation
```
gcloud version
```
Initiate config
```
gcloud init
```
Check by listing instances
```
gcloud compute instances list
```
### CFSSL
Have a read at [public key infrastructure](https://en.wikipedia.org/wiki/Public_key_infrastructure) \
\
Install with Homebrew
```
brew install cfssl
```
