# Phase 3 – Project Design

## Problem–Solution Fit

### Problem
Cricket player performance data is difficult to manage and analyse when it is stored in different files and formats.

### Solution
CRICKSTATS provides a centralized Salesforce-based platform to manage player details and match performance data.

## Proposed Solution

- Create custom **Player** and **Match Performance** objects.
- Establish a relationship between Player and Match Performance.
- Use Roll-Up Summary fields to calculate performance statistics.
- Create a Salesforce Lightning App named **CRICKSTATS**.
- Use automated Salesforce Flows.
- Provide interactive dashboards for performance analysis.
- Maintain centralized and secure player performance data.

## Data Flow Diagram

User → Salesforce UI → Player Object → Match Performance → Reports → Dashboard

## System Architecture

The system consists of:
- Salesforce Lightning UI
- Custom Salesforce Objects
- Relationships between objects
- Salesforce Flows
- Reports and Dashboards
- Salesforce Cloud

## Technology Stack

- Salesforce Lightning
- Salesforce Reports & Dashboards
- Salesforce Flows
- Salesforce Objects
- Salesforce Cloud
