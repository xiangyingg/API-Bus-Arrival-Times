# Bus Arrival Times: From API Data to Actionable Insight

## Executive summary

This project turns live bus arrival data into a practical decision-support tool for planning a journey from a selected bus stop to school. It combines an API-driven data pipeline built in **Alteryx** with an interactive **Power BI** dashboard, showing how raw transport data can be transformed into a clear and useful experience for both technical and non-technical audiences.

The project is not only about retrieving the next bus arrival. It demonstrates the complete analytics workflow: identifying a real-world question, collecting data, preparing and structuring it, and presenting the result in a format that supports a quick travel decision.

## Problem statement

When travelling to school, it is useful to know which bus services are approaching and how long it will be before the next bus arrives. However, raw bus stop API responses are designed for systems and developers rather than everyday users. The information must be cleaned, organised, and presented before it can answer a simple question:

> **Which bus should I take, and when will it arrive at my selected bus stop?**

This project addresses that gap by creating a repeatable pipeline and a consolidated dashboard for analysing bus arrival information at a selected stop on the journey to school.

## Why this analysis matters

Timely arrival information can support better journey planning, reduce uncertainty, and make public transport data easier to use. From an analytics perspective, the project also demonstrates how an API can become a reliable source for an end-to-end data product rather than remaining an isolated technical output.

The value of the project comes from connecting three stages:

1. **Data access** — retrieve bus arrival information from an API.
2. **Data preparation** — clean, transform, and structure the response for analysis.
3. **Decision support** — present the relevant information in an accessible dashboard.

## Project objectives

- Retrieve bus arrival data for a selected bus stop.
- Build a structured and repeatable data pipeline in Alteryx.
- Prepare the data so that arrival times can be interpreted consistently.
- Create a single Power BI view that is understandable to both technical and non-technical users.
- Demonstrate how data engineering and visual analytics can work together to answer a practical, everyday question.

## Workflow

```text
Bus stop API
      ↓
Alteryx data pipeline
      ↓
Cleaned and transformed arrival data
      ↓
Power BI dashboard
      ↓
Clear view of upcoming bus arrivals
```

### 1. Data source

Bus arrival information is collected from an API for the selected bus stop. The API provides the underlying operational data needed to identify upcoming services and their expected arrival times.

### 2. Data pipeline — Alteryx

Alteryx is used to retrieve, prepare, and organise the API response. This stage focuses on the technical data workflow, including transforming raw API data into a format suitable for reporting and analysis.

### 3. Dashboard — Power BI

The prepared data is presented in Power BI as an all-in-one interactive dashboard. The dashboard is designed to make the information accessible to a broad audience, including users who do not need to understand the technical pipeline behind the result.

## Expected outcomes and deliverables

The completed project delivers:

- A reusable Alteryx workflow for processing bus arrival API data.
- Structured output files containing the processed arrival information.
- A Power BI dashboard providing a consolidated view of upcoming bus services.
- A practical demonstration of how raw API data can be converted into an actionable travel-planning insight.

The repository includes:

- [`DDP_ASG2.yxzp`](./DDP_ASG2.yxzp) — Alteryx workflow package.
- [`DDP_ASG2 Frontend Display.pbix`](./DDP_ASG2%20Frontend%20Display.pbix) — Power BI dashboard.
- [`Frontend Display (time).xlsx`](./Frontend%20Display%20%28time%29.xlsx) — processed output in time format.
- [`Frontend Display (min).xlsx`](./Frontend%20Display%20%28min%29.xlsx) — processed output in minutes format.

## Audience and value

- **For technical audiences:** the project demonstrates API ingestion, data preparation, workflow design, and the creation of analysis-ready outputs in Alteryx.
- **For non-technical audiences:** the Power BI dashboard provides a single, accessible view of the information needed to understand upcoming bus arrivals.
- **For portfolio reviewers:** the project shows end-to-end ownership, from defining a real-world problem through to delivering a usable analytical product.

## Project takeaway

This project demonstrates that effective analytics is not just about collecting data or building a visualisation. It is about connecting a real user need to a reliable workflow and a clear outcome. By combining Alteryx and Power BI, the project transforms bus arrival API data into a practical tool for planning a journey to school and illustrates the broader value of data pipelines in everyday decision-making.
