# The Ultimate List of Everything!

`The Ultimate List of Everything!` is a sample project for the *Designing Applications for Kubernetes* course. Create your own fork of this project and follow along as we implement the [twelve-factor application design methodology](https://12factor.net/) in Kubernetes!

If you are running from a k8s node where firewalls are not opened for nodePorts, then do this tunneling (only for local testing)
`ssh -L 3000:localhost:30080 -L 3001:localhost:30081 -L 30081:localhost:30081 root@k8s-control-node`
