# Predictive Electric Vehicle Cooling System

## Overview

This project is based on the research topic:  
**"Predictive Electric Vehicle Cooling: Enhancing EV Range, Performance, and Battery Life."**

The primary goal is to design and test a predictive algorithm that intelligently activates the EV battery cooling system when needed, rather than relying on reactive temperature thresholds. This strategy can potentially improve battery longevity, driving range, and thermal performance.

---

## Objectives

-  Design a predictive model to forecast battery temperature.
-  Trigger cooling based on future heat buildup, not current temperature.
-  Simulate battery behavior during drive cycles.
-  Compare predictive vs reactive cooling methods.

---

##  How It Works

The core idea is to predict future battery temperature using time-series data (e.g., speed, ambient temperature, power draw) and trigger the cooling system before critical thresholds are reached.

> **Approaches Explored:**
> - Rule-based logic (thermal load thresholds)
> - Machine Learning (Linear Regression, Decision Trees)
> - LSTM (optional, for time-series prediction)

---

## Simulation

Simulations are run using synthetic driving and environmental data.  
Battery thermal behavior is modeled using simplified heat transfer equations and temperature profiles.

### Features:
- Modular Python scripts for model training and evaluation
- Jupyter Notebook with visual outputs
- Plots comparing predictive vs reactive cooling efficiency

---

## Project Structure

