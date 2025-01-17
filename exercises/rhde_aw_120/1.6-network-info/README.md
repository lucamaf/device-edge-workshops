# Workshop Exercise 1.6 - Gathering Network Information

## Table of Contents

* [Objective](#objective)
* [Step 1 - Introduction to the Workload](#step-1---introduction-to-the-workload)
* [Step 2 - The MQTT Broker](#step-2---the-mqtt-broker)
* [Step 3 - The Simulator](#step-3---the-simulator)
* [Step 4 - The Controller](#step4---the-controller)
* [Step 5 - The WebUI](#step-5---the-webui)
* [Step 6 - The Assembled Application](#step-1---the-assembled-application)


## Objective

In this exercise, we are going to gather the required information to be used for kickstarting our edge devices, whether physical devcies in the room or virtualized ones in AWS.

This exercise will cover

* What IP addresses/DNS records to use
* (If Applicible) What Network to use

### Step 1 - Grabbing Information for Physical Edge Devices

For the physical devices, an "edge manager" node should be available. This will have been configured by the workshop proviosioner before the lab was started. Your instructor should have the information ready for you.

In addition, the devices will be connected to the same network (wired or wireless) for provisioning and management. The instructor will be communicating this information to you as well.

### Step 2 - Network Information in AWS

For edge devices being virtualized in AWS, the "edge manager" node is the same as the node running Ansible Controller. DNS/DHCP should be available within the VPC of the edge hypervisor, so simply reuse that information.

> Note:
>
> A quick reminder: your Ansible Controller information can be found on your student page.

### Step 3 - Saving the Information

We'll need the networking information for kickstarting devices in a later exercise, so feel free to save this information somewhere handy or refer back to your student page/instructor provided information.

---
**Navigation**

[Previous Exercise](../1.5-application-info) | [Next Exercise](../1.7-coding-intro)

[Click here to return to the Workshop Homepage](../README.md)