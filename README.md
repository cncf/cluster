# CNCF Cluster Community

See the cluster request backlog: [![Cluster Request Backlog](https://badge.waffle.io/cncf/cluster.svg?label=ready&title=Ready)](http://waffle.io/cncf/cluster)

## About

The CNCF community cluster is deployed with the following intent in mind:

* Make available hardware for the community working on CNCF projects and related infrastructure.
* Make available hardware for the CNCF members needing to develop, debug and run cloud native software on relevant infrastructure at scale.
* Give users a staged path to first develop and test on a small scale and then at large.

## Submitting Requests

Simply file an [issue](https://github.com/cncf/cluster/issues) here and fill out the details mentioned in the issue template.

## Cluster Governance Council

* Bryan Cantrill
* Jason Mendenhall
* Jonathan Donaldson

## Hardware

### Compute Node Spec

* 2x Intel E5-2680v3 12-core
* 256GB RAM
* 2x Intel S3610 400GB SSD
* 1x Intel P3700 800GB NVMe PCIe SSD
* 1x QP Intel X710

### Storage Node Spec

* 2x Intel E5-2680v3 12-core
* 128GB RAM
* 2x Intel S3610 400GB SSD
* 10x Intel 2TB NLSAS HDD
* 1x QP Intel X710"

## Expectations

The following is expected from the CNCF cluster users:

* The cluster is used for the purposes of open source projects only. CNCF related projects and projects demonstrating intent of upstreaming code will be given priority.
* Users of the cluster preserve the rare value that the cluster represents: size and bare metal consumption.
* Users will not tamper or misuse the infrastructure. The governance committee will closely monitor usage and WILL blacklist users or organizations from using the cluster if they detect any misuse or tampering.
* Users will need to return the servers back to a well-defined and understood baseline, post use.
* Users ensure that no proprietary software or data on the cluster is intentionally exposed. Neither CNCF nor Intel bears the responsibility for exposure of proprietary information under any circumstances.
* We do not expect any physical changes to be requested of the cluster. Hence, there is no expectation of on-site presence.
* Agree to the [Terms of Use](TERMS_OF_USE.md)
