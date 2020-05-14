# Agent Check: Fairwinds Insights

## Overview

This is the integration with [Fairwinds Insights][1].

## Setup

### Installation

The Fairwinds Insights integration does not require anything new to be installed.

### Configuration

Login to [Insights][1] and navigate to the settings page for your organization and input your Datadog API key in the section marked Datadog.

### Validation

After providing your API key to Insights an initial Event should appear in Datadog showing that the integration is setup.

## Data Collected

### Metrics

Action Items from Insights will appear in Datadog with tags so that you can perform any analysis you need.

### Service Checks

Fairwinds Insights does not include any service checks.

### Events

An initial Event will appear when you first setup the integration and then there will be a new Event every time a new Action Item is discovered in Insights and every time an Action Item is fixed.

## Troubleshooting

Need help? Contact [Fairwinds][2].

[1]: https://insights.fairwinds.com
[2]: https://fairwinds.com
