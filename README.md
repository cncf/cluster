# CNCF Community Infrastructure Lab (CIL)

> **⚠️ IMPORTANT NOTICE: The CNCF Community Cluster is being sunset and will be decommissioned on December 31, 2025.**
> 
> **Timeline:**
> - **September 30, 2025**: Projects must migrate to alternative cloud platforms
> - **November 21, 2025**: All remaining resources will be removed by CNCF staff
> - **December 31, 2025**: Complete decommissioning of the CNCF Community Cluster
> 
> For more information and alternative infrastructure options, please see our [farewell blog post](https://www.cncf.io/blog/2025/06/04/thank-you-equinix-metal-the-cncf-community-bids-farewell-to-the-bare-metal-cluster/) and visit [CNCF Project Services & Hosted Tools](http://contribute.cncf.io/resources/project-services/hosted-tools/#cloud-infrastructure).

The CNCF Community Infrastructure Lab (CIL) **provided** free access to state-of-the-art computing resources for open source developers working to advance cloud native computing. We **offered** access to both x86 and ARMv8 bare metal servers for software builds, continuous integration, scale testing, and demonstrations for the CNCF projects.

The on-demand infrastructure resource **was** generously contributed and managed by [Equinix Metal](https://metal.equinix.com/), a leading bare metal cloud, as part of its commitment to the cloud native and open source communities. The resources **were** available from 15 locations across the globe; including New York City, Silicon Valley, Amsterdam, and Tokyo. It **allowed** developers extended testing or the ability to build out continuous integrated infrastructure with the automation and consistency of big public clouds without being required to use virtualization. They **offered** a variety of hardware [types](https://metal.equinix.com/product/servers/).

~~[Apply to Use the On-Demand Infrastructure](https://github.com/cncf/cluster/issues/new?assignees=caniszczyk%2C+jeefy%2C+krook%2C+idvoretskyi&labels=cluster+request&projects=&template=cncf-community-lab-cluster-request.md&title=)~~

**New applications are no longer being accepted. Please see alternative infrastructure options at [CNCF Project Services & Hosted Tools](http://contribute.cncf.io/resources/project-services/hosted-tools/#cloud-infrastructure).**

~~Request access and then get up and running in minutes!~~

**The CNCF Community Cluster is no longer accepting new requests and will be decommissioned on December 31, 2025.**

## Infrastructure benefits (Historical)

The CNCF Community Infrastructure Lab **provided** the following benefits:

- **Allowed** developers extended testing or the ability to build out continuously integrated infrastructure with the automation and consistency of big public clouds without needing to use virtualization.
- **Could be leveraged** to curate server configurations for different use cases, test new protocols without layers of complexity, and integrate with leading cloud and developer tools.
- Developers **also had** the ability to bring their own image or operating system and have complete control of the cluster, enabling them to test across different environments simultaneously.
- Based on their testing needs, developers **could choose** from five server configurations offering different sizes, platform features, and architectures (e.g., x86 and ARMv8).
- Each bare metal configuration **was** API driven, cloud native friendly and **took** less than 10 minutes to deploy.
- Equinix Metal **did not impose** multi-tenancy, virtualization, or an overlay network by default - enabling users to bring the tooling of their choice.
- Carrier-grade features like the ability to announce your own IP space, BGP/Anycast, and native IPv6 support **were also included**.

## Migration and Alternatives

**For current users of the CNCF Community Cluster, please note the following migration timeline:**

- **September 30, 2025**: Projects must shut down and migrate any of their resources to an alternative cloud platform
- **November 21, 2025**: All remaining resources will be removed by CNCF staff (the week after KubeCon North America)
- **December 31, 2025**: The CNCF Community Cluster will be completely decommissioned

**Alternative infrastructure options are available through:**
- [CNCF Project Services & Hosted Tools](http://contribute.cncf.io/resources/project-services/hosted-tools/#cloud-infrastructure)
- [Oracle OCI Credits for CNCF Projects](https://www.cncf.io/blog/2024/02/02/oracle-oci-credits-are-now-available-to-cncf-projects-here-is-what-you-need-to-know/)
- GitHub-hosted runners with GitHub Actions
- CNCF-provided GitHub Runners

## Usage guidelines (Historical Reference)

**Note: These guidelines applied when the cluster was operational.**

- Code being run **must be** 100 percent open source and **must not include** any sensitive data.
- Testing **should involve** cloud native computing, meaning containerization, microservices, orchestration or some combination.
- You **agree to write** a blog post later about your experiences with the CIL.
- The infrastructure **is being provided** to CNCF Projects only
  - Priority **is given** first to [CNCF Graduated and Incubating projects](https://www.cncf.io/projects/) then [CNCF Sandbox projects](https://www.cncf.io/sandbox-projects/).
- Resources **are limited** so we **may ask** you to reduce your usage when there is high demand for the available credits from Equinix Metal ($1,000,000 per year).
- If the purpose of using the provided infrastructure **is** CI/CD, please **consider using** the GitHub-hosted runners with GitHub Actions first, or the CNCF-provided GitHub Runners - <https://contribute.cncf.io/resources/newsletters/2024-02-21-projectnewsletter/#github-action-runners>

---

## Thank You

We extend our sincere appreciation to the Packet and Equinix Metal teams for their years of generous support. This freely available infrastructure empowered countless open source projects beyond cloud native, fueling innovation and enabling maintainers to push boundaries.

For more information about the cluster sunset, please read our [farewell blog post](https://www.cncf.io/blog/2025/06/04/thank-you-equinix-metal-the-cncf-community-bids-farewell-to-the-bare-metal-cluster/).
