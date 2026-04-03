# Overview

This repository contains a walkthrough of deploying a full Zabbix monitoring environment using two Ubuntu virtual machines:
one acting as the Zabbix Server and the other as a LAMP stack monitored host.
The lab demonstrates how to install, configure, and validate a working monitoring setup using modern Zabbix components.

The accompanying document includes screenshots, configuration notes, troubleshooting steps, and reflections on the process.

# What This Lab Covers

The full write‑up walks through the following major stages:

1. Preparing the Environment
Updating both VMs, confirming connectivity, and ensuring the base system is ready for monitoring.

2. Installing Required Components
A high‑level overview of installing:

    - MySQL

    - Zabbix Server

    - Zabbix Frontend

    - Zabbix Agent

The document explains the purpose of each component and how they interact.

3. Database & Server Configuration

A summary of:

    - Creating the Zabbix database

    - Creating the Zabbix DB user

    - Importing the initial schema

    - Updating Zabbix server configuration

4. Agent Deployment on the LAMP Host
Covers installing the Zabbix Agent, configuring Apache for monitoring, and enabling communication between the two machines.

5. Enabling Persistence & Firewall Rules
Ensuring all services start on boot and that required ports are open.

6. Adding the Host in the Zabbix Frontend
Explains how the agent is added through the GUI and how Zabbix begins collecting metrics.

7. Creating a Web Scenario
A simple web check is created to generate events and demonstrate Zabbix’s web monitoring capabilities.

8. Exploring Dashboards

Screenshots and commentary show:

    - Global dashboards

    - Problem logs

    - Host metrics

    - Web scenario results

A custom dashboard created during the lab
