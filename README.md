We already know that applications can be tied to a Github repo based on Channels and Subscriptions, but it hasn't been clear on how to do the same thing with Governance policies.  That is to create a GitHub repo (channel) which contains policy (YAML) definitions that can be pulled into ACM.

https://github.com/kcalliga/acm-git-demos/tree/main/htpasswd-policy-generator
https://github.com/kcalliga/policy-collection/tree/main/my-policies
https://www.myopenshiftblog.com/advanced-cluster-management-updates/

In part2 of this series, I wanted to show you how to configure the Central Infrastructure Management/Assisted-Service to handle the discovery and provisioning of bare-metal resources that can eventually be consumed to be part of an OCP cluster.  This blog-post outlines how to setup the CIM/Assisted-Service including the bare-metal/cluster YAML definitions.  ACM has a GUI that generates these various YAML definitions (infrastructureenvironment, klusterlet, agentclusterinstall, etc) for you. This part will be covered here with a re-hash of some information based on that previous article.

https://www.myopenshiftblog.com/advanced-cluster-management-updates-part-2-of-2/

