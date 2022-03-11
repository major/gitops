# Major's Gitops

This repo contains several applications that I deploy to a [kubernetes] environment at
[DigitalOcean]. I use [flux] to manage the deployment and all secrets are encrypted with
[SOPS] and [age].

The cluster costs just under $50 per month to run, including three droplets, a load
balancer, and a small amount of block storage.

[kubernetes]: https://kubernetes.io/
[DigitalOcean]: https://www.digitalocean.com/
[flux]: https://github.com/fluxcd/flux2
[SOPS]: https://github.com/mozilla/sops
