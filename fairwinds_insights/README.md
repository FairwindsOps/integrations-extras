# Agent Check: Fairwinds Insights

## Overview

This is the integration with [Fairwinds Insights][1].

Fairwinds Insights is a Kubernetes configuration validation platform that proactively monitors your Kubernetes and container configurations and recommends improvements.

The software combines trusted open source tools, toolchain integrations, and SRE expertise based on hundreds of successful Kubernetes deployments. 

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

## Troubleshooting

Need help? Contact [Fairwinds][2].

[1]: https://insights.fairwinds.com
[2]: https://fairwinds.com
