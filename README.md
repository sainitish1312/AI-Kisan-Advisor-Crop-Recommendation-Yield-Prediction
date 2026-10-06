# 🌾 AI Kisan Advisor – Crop Recommendation & Yield Prediction

### AI-Driven Decision Support for Sustainable and Data-Driven Farming

AI Kisan Advisor is an AI-powered agricultural decision-support prototype designed to help farmers make more informed crop-planning decisions using soil, climate, crop, market, and financial parameters.

The system combines machine learning concepts, explainable AI, agricultural analytics, and financial modelling to provide crop recommendations, expected yield estimates, economic comparisons, and alternative crop options.

---

## 🎥 Project Demo

The working prototype demonstrates:

- Farmer and farm-condition inputs
- Soil and climate parameter processing
- Crop recommendation
- Recommendation confidence scoring
- Expected yield prediction
- Market price and risk assessment
- Investment and revenue estimation
- Profit and ROI analysis
- Alternative crop recommendations
- Explainable recommendation reasoning

▶️ **[Watch the AI Kisan Advisor Demo](https://youtu.be/uz3Jgbbk11M)**

> The demo presents prototype outputs intended to demonstrate the decision-support workflow. The results should not be treated as professional agricultural advice.

---

## 📌 Project Overview

Agricultural decision-making can be affected by fragmented information, delayed advisory services, generic recommendations, inefficient resource utilization, and limited access to data-driven insights.

AI Kisan Advisor addresses this challenge by bringing relevant agricultural and business parameters together into a single decision-support workflow.

The proposed system considers factors such as:

- Soil characteristics
- Temperature
- Humidity
- Rainfall
- Previous crop
- Farm area
- Crop characteristics
- Market conditions
- Estimated investment
- Expected revenue
- Profitability
- ROI
- Risk

The objective is to help users compare potential crop choices from both an agricultural and economic perspective.

---

## 🎯 Problem Statement

Farmers often need to make crop-selection decisions under uncertainty while considering soil conditions, weather, water availability, expected yield, market prices, and profitability.

The project identifies several challenges:

- Delayed access to agricultural information
- Generic or non-personalized recommendations
- Inefficient utilization of agricultural resources
- Yield losses caused by suboptimal crop selection
- Limited integration of soil and climate information
- Lack of transparency in some AI-based recommendations
- Difficulty comparing agricultural alternatives economically

AI Kisan Advisor proposes a data-driven decision-support approach to address these challenges.

---

## 🎯 Project Objectives

### Technical Objectives

- Develop a crop recommendation system
- Develop a yield prediction component
- Provide explainable AI-based recommendations
- Generate confidence scores for recommendations
- Compare alternative crop choices
- Evaluate potential economic outcomes
- Demonstrate an AI-agent-based decision workflow

### Business Objectives

- Support data-driven agricultural decision-making
- Improve resource-utilization decisions
- Compare crop alternatives economically
- Estimate potential profitability
- Explore a scalable agricultural technology solution
- Support sustainable farming decisions

---

## 🧠 Solution Overview

The prototype follows a three-layer decision-support architecture:

```text
┌──────────────────────────────────────────────┐
│           DATA INPUT & INGESTION             │
│                                              │
│  Soil parameters                             │
│  N, P, K, pH                                 │
│  Temperature                                 │
│  Humidity                                    │
│  Rainfall                                    │
│  Previous crop                               │
│  Farm information                            │
└──────────────────────┬───────────────────────┘
                       │
                       ▼
┌──────────────────────────────────────────────┐
│          AI / PREDICTION ENGINE              │
│                                              │
│  Crop recommendation                         │
│  Yield prediction                            │
│  Confidence assessment                       │
│  Feature/parameter analysis                  │
│  Explainable decision support                │
│  Agent-based reasoning workflow              │
└──────────────────────┬───────────────────────┘
                       │
                       ▼
┌──────────────────────────────────────────────┐
│            RECOMMENDATION OUTPUT             │
│                                              │
│  Recommended crop                            │
│  Confidence score                            │
│  Expected yield                              │
│  Market information                          │
│  Risk assessment                             │
│  Alternative crops                           │
│  Economic comparison                         │
│  Estimated profit & ROI                      │
└──────────────────────────────────────────────┘
