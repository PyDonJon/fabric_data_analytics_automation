# Energy Operations Alerting (Microsoft Fabric + Power Automate)
Automated BI with Microsoft Fabric, Power Automate and Power BI.

## Overview
This project implements an automated operational alerting workflow using
Microsoft Fabric semantic models and Power Automate.

The goal is to detect energy deficit conditions from analytical measures
and trigger alerts to stakeholders based on defined thresholds.

## Architecture
- Microsoft Fabric Semantic Model (Power BI dataset)
- DAX-based analytical measures
- Power Automate scheduled flow
- Conditional alert evaluation

## Key Features
- Queries Fabric semantic models using DAX
- Safely handles null and missing values
- Applies business thresholds for alerting
- Designed for production scheduling and extension

## Technologies
- Microsoft Fabric
- Power BI / DAX
- Power Automate
- JSON parsing & expression language

## Status
This project was developed in a trial environment.
Live execution is not publicly available, but all logic,
queries, and flow structure are documented and reproducible.
