# promethus-setup
## Prometheus, Node-Exporter Setup Guide
This guide provides step-by-step instructions for setting up various components of a monitoring stack including Prometheus and Node-Exporter.

## Prerequisites
Before you begin, ensure you have the following prerequisites:

Access to a Linux-based server (physical or virtual)
I choose to create an EC2 instance that has the following:
    - Ubuntu as an operating system
    - A security group that allows
        - port 9090 for promethus
        - port 9100 for node_exporter