# Salesforce Admin Pipeline

This project demonstrates the configuration and administration of a Salesforce CRM system designed to manage a sales pipeline. The goal of this project is to simulate real world Salesforce administration tasks including object configuration, data management, automation, and reporting.

## Project Overview

The system models a basic sales workflow where leads are captured, qualified, converted into opportunities, and tracked through the sales pipeline. It also includes automation and validation rules to maintain data quality and improve operational efficiency.

This project was created to showcase core Salesforce Administrator capabilities.

## Features Implemented

### Custom Object Configuration
Created a custom **Retailer** object to represent partner retailers and manage their information.

Fields implemented:
- Industry
- Region
- Tier
- Active Status

### Lead Management
Extended the standard Lead object with additional fields to support qualification and routing.

Fields added:
- Region
- Lead Score
- Qualified

### Opportunity Pipeline
Configured opportunity tracking with additional deal attributes.

Fields added:
- Deal Type
- Discount Percentage

### Data Integrity
Implemented validation rules to enforce business logic and maintain clean data.

Example:
- Opportunities marked as Closed Won must include an Amount value.

### Automation
Built a **Salesforce Flow** to automatically assign leads to sales representatives based on geographic region.

Example logic:
- Canada East → Sales Rep East
- Canada West → Sales Rep West

### Reporting and Dashboards
Created reports and dashboards to monitor sales pipeline performance.

Reports include:
- Leads by Source
- Leads by Region
- Opportunity Pipeline by Stage

Dashboard visualizes:
- Lead distribution
- Sales pipeline value
- Regional lead ownership

## Skills Demonstrated

- Salesforce Object Configuration
- Field Creation and Page Layout Management
- Data Quality Enforcement
- Salesforce Flow Automation
- User Permissions and Access Management
- Report and Dashboard Development
- CRM Data Modeling

## Purpose

This project was built as part of a Salesforce Administrator portfolio to demonstrate practical CRM administration skills such as configuration, automation, and reporting within a Salesforce environment.
