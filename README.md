# K3d

Learning kubernetes by using its small variant k3d.

## Description

k3d is a lightweight wrapper to run k3s (Rancher Lab’s minimal Kubernetes distribution) in docker.
k3d makes it very easy to create single- and multi-node k3s clusters in docker, e.g. for local development on Kubernetes.

## Getting Started

### Requirements

* [docker](https://docs.docker.com/install/) to be able to use k3d at all
* [kubectl](https://kubernetes.io/docs/tasks/tools/#kubectl) to interact with the Kubernetes cluster

### Installing

```
sudo apt install docker.io
sudo usermod -aG docker $USER
curl -s https://raw.githubusercontent.com/rancher/k3d/main/install.sh | bash
```

## Help

If you have problems or are stuck somewhere, check out the documentation.


## Authors

Contributors names and contact info

ex. Leonardo Wolo  
ex. [@Linkedin](https://www.linkedin.com/in/leonardo-wolo-b1b7a11a0/)


## License

This project is just a local test setup. Don't use this in real production deployment.
