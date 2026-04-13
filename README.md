# Azure-cloud-monitoring-Alerting
Azure-based cloud monitoring and alerting project using Azure Monitor, VM metrics, alert rules, and automated email notifications.
# Azure Cloud Monitoring & Alerting Project

## Project Overview

This project demonstrates the implementation of a real-time cloud monitoring and alerting solution using Microsoft Azure. The objective was to monitor infrastructure performance, detect abnormal CPU utilization, and trigger automated notifications for proactive incident response.

---

## Architecture

**Workflow:**

User Traffic → Azure Virtual Machine → Azure Monitor Metrics → Alert Rule → Action Group → Email Notification → Dashboard Visualization

---

## Technologies Used

* Microsoft Azure
* Azure Virtual Machines
* Azure Monitor
* Action Groups
* Azure Dashboard
* Nginx
* Linux (Ubuntu)

---

## Features Implemented

* Provisioned an Azure Virtual Machine to host the monitored infrastructure
* Installed and configured Nginx web server on the VM
* Enabled real-time performance monitoring using Azure Monitor
* Created CPU-based metric alert rules for anomaly detection
* Configured Action Groups for automated email notifications
* Built dashboard visualizations for infrastructure performance tracking
* Simulated high CPU workload using stress testing to validate alert functionality

---

## Step-by-Step Implementation

### 1. Virtual Machine Provisioning

* Created Azure Virtual Machine using Ubuntu OS
* Configured networking and inbound security rules
* Assigned public IP for external access

### 2. Web Server Deployment

* Installed Nginx on the VM
* Verified successful deployment using browser access

### 3. Monitoring Configuration

* Enabled Azure Monitor metrics for VM performance tracking
* Monitored CPU utilization and performance behavior

### 4. Alerting Setup

* Created CPU threshold-based alert rule
* Defined alert evaluation frequency and severity

### 5. Notification Integration

* Configured Azure Action Group
* Added email notification receiver
* Linked Action Group to Alert Rule

### 6. Dashboard Creation

* Built Azure Dashboard for performance visualization
* Added CPU and infrastructure monitoring graphs

### 7. Validation Testing

* Installed stress tool on VM
* Simulated high CPU utilization
* Verified alert trigger and email notification delivery

---

## Screenshots


* VM Overview
* Nginx Running
* Alert Rule Configuration
* Action Group Setup
* Alert Triggered
* Metrics Graph
* Dashboard

---

## Key Skills Demonstrated

* Cloud Monitoring
* Incident Detection & Alerting
* Azure Infrastructure Management
* Infrastructure Troubleshooting
* Performance Monitoring
* Cloud Operations

---

## Outcome

Successfully implemented a real-time cloud monitoring and alerting system capable of detecting infrastructure performance issues and notifying stakeholders through automated alerts.


