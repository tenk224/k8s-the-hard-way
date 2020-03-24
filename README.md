# Kubernetes the hard way
## Disclaimer
- For learning kubernetes purpose, use the repository as you please.
- I will provide steps that I have done in MacOS and partially in Windows Subsystem for Linux (WSL).
- This will be deployed to Google Cloud Platform (GCP)
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
Or brew
```
brew install google-cloud-sdk
```
Check installation
```
gcloud version
```