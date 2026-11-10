# Slide

### Sports modeling, data pipelines, and forecast evaluation

[Back to my profile](https://github.com/Boat1x)

**Type:** Personal engineering project  
**Scope:** NBA and NHL analytics  
**Status:** Active development · Private source

## The problem

A forecast needs more than a single predicted score. Sports data changes, player availability affects outcomes, and related events can move together. Slide explores how to turn these inputs into statistical forecasts and communicate the uncertainty through an application.

## What I am building

The project combines Python data and modeling workflows with a TypeScript application. It includes NBA forecasting and an NHL module, with work on player projections, simulation, input validation, and evaluation.

The central engineering questions are whether the inputs are appropriate for the prediction time, whether the output is consistent with the model, and whether performance holds up on data the model did not use for fitting.

## Engineering themes

| Area | Focus |
| --- | --- |
| **Data pipelines** | Turn game, player, and availability data into consistent model inputs. |
| **Forecast distributions** | Represent a range of possible outcomes and relationships between them. |
| **Evaluation** | Compare predictions with observed results and inspect performance over time. |
| **Input quality** | Handle missing, stale, or incomplete data explicitly. |
| **Application design** | Present projections, assumptions, and limitations in a form a user can inspect. |

## Model maturity

The NHL module is an experimental statistical baseline. The NBA and NHL components are at different stages of development, with evaluation ongoing.

## Technical focus

Python · SQL · TypeScript · Statistical modeling · Simulation · Data validation · Evaluation tooling

