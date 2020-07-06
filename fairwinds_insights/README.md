# Agent Check: Fairwinds Insights

## Overview

Validate your Kubernetes configurations

Improve your security posture

*  Scan containers for vulnerabilities
* Validate deployment configurations
* Audit clusters for weaknesses

Reduce costs

* Gain visibility into application resource usage
* Determine the right CPU and memory settings for your workloads

Save time

* Integrate Kubernetes configuration recommendations with your existing Datadog dashboards
* Improve collaboration with Slack integration

## Pricing

There is a free 30-day trial for the Professional edition and then variable pricing applies. A limited Community (free) version is available for up to 6 nodes. For more details, reach out to sales@fairwinds.com.

## Setup

### Installation

Login to Fairwinds Insights and navigate to your Organization's Settings page, then enter your Datadog API key in the API Key field under the Datadog section.

### Configuration

Login to [Fairwinds Insights][1] and navigate to the settings page for your organization and input your Datadog API key in the section marked Datadog.

### Validation

After providing your API key to Insights an initial Event should appear in Datadog showing that the integration is set up.

## Data Collected

### Metrics

Action Items from Fairwinds Insights will appear in Datadog with tags so that you can perform any analysis you need.

### Service Checks

Fairwinds Insights does not include any service checks.

### Events

* An initial Event will appear when you first setup the integration
* Event per new Action Item in Fairwinds Insights
* Event per event fixed Aciton Item in Fairwinds Insights

## Support

We recommend taking a look at our [documentation](https://insights.docs.fairwinds.com/), which covers setup and integration as well as ongoing usage to get the most out of Fairwinds Insights

If you still need help, we are happy to answer any questions you have regarding configuration validation or Kubernetes in general. Please reach out.

Phone: +1 617-202-3659
Email: sales@fairwinds.com

### Frequently Asked Questions

**How does Fairwinds Insights work?**

Fairwinds Insights provides a unified, multi-cluster view into three categories of Kubernetes configuration issues: security, efficiency, and reliability. Fairwinds Insights makes it easy to deploy multiple open-source tools through a single helm installation. This one-time install helps engineers avoid custom work for installing and configuring each tool. 
 
**What’s a plugin?**

Fairwinds Insights refers to the tools integrated with the software as ‘plugins.’

**What’s an Agent?**

Fairwinds Insights refers to the included helm chart as the ‘Fairwinds Insights Agent.’

**What happens to my data?**

Fairwinds Insights aggregates findings from each plugin and publishes it into a multi-cluster view for easy consumption, prioritization, and issue tracking.

**What plugins does Fairwinds Insights include?**

Fairwinds Insights provides integrations for a variety of great open source tools you use today, including [Polaris](https://github.com/FairwindsOps/polaris), [Goldilocks](https://github.com/FairwindsOps/goldilocks/), and [Trivy Container Scanning](https://github.com/aquasecurity/trivy). For the complete list, please visit the [Fairwinds Insights documentation center](https://insights.docs.fairwinds.com/). Just a few of the example findings are listed below:

* Container vulnerabilities
* Security issues with Kubernetes deployments (e.g., deployments configured to run as root)
* Cluster-level weaknesses (e.g., exposed pods, information disclosures, etc.)
* Kubernetes CVEs
* Automated notification of Helm charts that are out of date

[1]: https://insights.fairwinds.com