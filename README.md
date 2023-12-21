### Cilium dual-stack k3s pi-setup

This repository serves as demo material to set up a vanilla/lightweight dual-stack kubernetes(k3s) configuration on a PI or any other compatible computing device.
You can add more k3s-nodes to achieve high-availability if needed. In the end a ipv4/ipv6 Nextcloud instance is configured to test the dual-stack functionality.

Everything has mostly been restricted to homelab use, but can easily be adjusted to fit your needs.

This guide also focuses heavily on `Cilium` which is an open source, cloud native solution for providing, securing, and observing network connectivity between workloads, fueled by the revolutionary Kernel technology eBPF. If you just want to setup k3s with default network layer in k3s, you can just remove the following lines in `k3s/config.yaml`

All components mentioned/used in this blogpost can easily be updated to a newer version if you change the version number.



Blogpost/guide link can be found here.


