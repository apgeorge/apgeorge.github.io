---
layout: post
title: "Current Project Highlights"
date: 2014-01-31 12:00:01 +0530
comments: true
published: false
categories: 
---


### Fully automated Continuous Delivery setup from build to Production using Chef Server, Go, and LXCs.

* CD pipelines for both application as well as the Chef cookbooks

### Deployments

* Deployments using Chef.
* Application artifacts packaged as RPMs uploaded to a local RPM server which makes application deployments as simple as a regular RPM install and so can be done by Chef itself. No need for another tool to do deploys.
* Application version passed to Chef client through Chef Environment attributes.
* Blue Green deployments through Go deployment pipeline with both stacks actively serving live traffic.

### Testing

* Acceptance testing on production-like mini-environment setup using Linux Containers (LXCs) on a single Go Agent.

### Infrastructure CD Pipeline
* Chef Cookbooks CD pipeline through Foodcritic, ruby syntax checks, rspec and integration testing of chef convergence through Test Kitchen and Docker.
* Rspec tests to test a newly provisioned environment.


### Monitoring

* Monitoring through Ganglia and Nagios alerting based off Ganglia metrics.
* Application metrics are captured along with system metrics. Deployments are tracked as events overlaid on graphs.
* Centralized Log aggregation through Splunk.


### Caching

* Akamai as CDN



