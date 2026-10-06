# AI Kisan Advisor – Crop Recommendation & Yield Prediction

### AI-Driven Decision Support for Sustainable Farming

An AI-powered agricultural decision-support system that uses machine learning to recommend suitable crops and predict expected yield based on soil and climate conditions, while providing explainable recommendations for farmer decision-making.

---

## 📌 Project Overview

**AI Kisan Advisor** is an Artificial Intelligence in Business project focused on addressing the information and decision-making gap faced by farmers.

The proposed system integrates soil, climate, and crop-related parameters with machine learning to provide:

- 🌱 Crop recommendations
- 📈 Expected yield predictions
- 🔍 Explainable AI-based reasoning
- 💰 Economic comparison of crop alternatives
- 📊 Data-driven agricultural decision support

The project combines **machine learning, business analysis, sustainability, explainable AI, and financial modelling** to develop an accessible solution for precision agriculture.

---

## 🎯 Problem Statement

Agricultural decision-making is often affected by fragmented information, delayed advisories, generic recommendations, and inefficient use of resources.

The project identifies key challenges including:

- Delayed access to actionable agricultural information
- Generic district-level recommendations
- Inefficient use of water and fertilizers
- Yield losses caused by suboptimal crop selection
- Limited integration of soil and climate information
- Lack of transparency in some AI-based agricultural solutions
- Adoption and affordability barriers for smallholder farmers

AI Kisan Advisor aims to address these challenges through a proactive, data-driven decision-support system.

---

## 🎯 Project Objectives

### Technical Objectives

- Achieve high-accuracy crop classification
- Develop a robust yield prediction model
- Provide explainable AI-based recommendations
- Reduce recommendation response time
- Validate model performance using appropriate evaluation metrics

### Business Objectives

- Develop an economically viable agricultural AI solution
- Support agricultural cooperatives and farmers
- Improve resource efficiency
- Increase potential agricultural productivity
- Develop a scalable B2B2C business model

---

# 🧠 Solution Overview

The proposed system follows a three-layer architecture:

```text
┌─────────────────────────────────────┐
│       DATA INGESTION & INPUT        │
│                                     │
│  Soil N, P, K, pH                   │
│  Temperature                        │
│  Humidity                           │
│  Rainfall                           │
└──────────────────┬──────────────────┘
                   │
                   ▼
┌─────────────────────────────────────┐
│        AI PREDICTION ENGINE         │
│                                     │
│  Random Forest                      │
│  Crop Classification               │
│  Yield Prediction                  │
│  Feature Importance                │
│  Explainable AI                    │
└──────────────────┬──────────────────┘
                   │
                   ▼
┌─────────────────────────────────────┐
│        RECOMMENDATION OUTPUT        │
│                                     │
│  Recommended Crop                  │
│  Confidence Score                  │
│  Alternative Crops                 │
│  Expected Yield                    │
│  "Why This Crop?" Explanation      │
│  Economic Comparison               │
└─────────────────────────────────────┘
