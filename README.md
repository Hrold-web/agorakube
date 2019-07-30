# Ilki-Kube

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

This project is aimed to provide the simplest way to install kubernetes on bare-metal systems.
Actually, only Ubuntu 18.04 (Bionic) amd64 is supported, but many other systems will be available soon.


This project is still under development. 
Feedback is very welcome via the
[GitHub site](https://github.com/pierreilki/k8s-distrib-2)
as issues or pull (merge) requests.


## Summary

This is a list of points that will be explained in this Readme file for the Ilki-Kube project :

- What is IlkiKube
- How to get it
- How to give feedback
- How to contribute
- Licence

## What is IlkiKube

IlkiKube is an easy-to-use, stable Kubernetes distribution.
By its symplicity, IlkiKube provide a good way to deploy and manage K8S CLusters.
IlkiKube is based on Ansible scripts that install and configure Kubernetes componants (control plane and data plane) quickly on bare-metal / VMs / Cloud Instances, as systemd services.
Many options are customizable, like DNS Service (default: CoreDNS), Ingress (default: Traefik), Runtime (Default: Containerd), certificats,...
This project is actually under development, ans only Ubuntu 18.04 (Bionic) - amd64 system is syported. Other systems will be added soon.

## How to get it



## How to give feedback

This project is still under development. 
Feedback is very welcome via the
[GitHub site](https://github.com/pierreilki/k8s-distrib-2)
as issues or pull (merge) requests.

## How to contribute

This project is still under development. 
Contributions are very welcome via the
[GitHub site](https://github.com/pierreilki/k8s-distrib-2)
as issues or pull (merge) requests.

## License

All material here is released under the [APACHE 2.0 license](./LICENSE).
All material that is not executable, including all text when not executed,
is also released under the APACHE 2.0.
In SPDX terms, everything here is licensed under APACHE 2.0;
if it's not executable, including the text when extracted from code, it's
"(APACHE 2.0)".

Like almost all software today, this software depends on many
other components with their own licenses.
Not all components we depend on are APACHE 2.0-licensed, but all
*required* components are FLOSS. We prevent licensing issues
using various processes (see [CONTRIBUTING](./CONTRIBUTING.md)).
