# 🧠 Smart CPG Decision Support Agent

### GenAI + Agentic AI + Databricks + Simulation Engine

------------------------------------------------------------------------

## 🚀 Project Overview

This project builds an intelligent **Decision Support Agent** for a
Consumer Packaged Goods (CPG) business using:

-   📊 PySpark (Data Engineering)
-   🧪 What-If Simulation Modeling
-   🤖 Generative AI (Databricks GPT OSS)
-   🧠 Agentic AI (Tool Selection + Reasoning Loop)
-   💬 CLI-based Conversational Interface
-   ✅ Structured Testing Framework

The system enables stakeholders to:

-   Analyze multi-store, multi-SKU sales data
-   Detect trends and seasonality
-   Simulate pricing, promotion, and supply scenarios
-   Generate executive-level strategy memos
-   Interact conversationally with an AI agent

------------------------------------------------------------------------

# 🏗 Architecture

Data Layer (Bronze → Silver → Gold)\
↓\
Simulation Tools Layer\
↓\
LLM Layer (Databricks GPT OSS)\
↓\
Agent Layer (Tool Selection + Memory)\
↓\
CLI Chatbot Interface

------------------------------------------------------------------------

# 📊 Data Layer

Synthetic dataset simulating:

-   3 years of daily sales
-   10 stores
-   50 SKUs
-   5 product categories
-   Promotional campaigns
-   Inventory levels
-   Holiday flags

### Medallion Architecture

-   🥉 Bronze: Raw CSV ingestion\
-   🥈 Silver: Cleaned & transformed dataset\
-   🥇 Gold: Aggregated & business metrics

Tables Created:

-   cpg_sales_silver
-   cpg_sales_gold_monthly
-   cpg_sales_gold_promo
-   cpg_sales_gold_region

------------------------------------------------------------------------

# 🔥 Simulation Engine

### 1️⃣ Price Increase Simulation

-   Elasticity-based demand adjustment
-   Revenue impact calculation

### 2️⃣ Promotion Uplift Simulation

-   Volume boost modeling
-   Financial impact estimation

### 3️⃣ Supply Shortage Simulation

-   Inventory-constrained demand
-   Revenue drop modeling

### 4️⃣ Combined Strategy Simulation

-   Multi-variable impact modeling

Example Output Structure:

{ "simulation_type": "...", "baseline_revenue": ...,
"projected_revenue": ..., "revenue_impact_percent": ... }

------------------------------------------------------------------------

# 🤖 Agentic AI Layer

The agent:

-   Interprets business questions
-   Selects the appropriate simulation tool
-   Executes simulation
-   Sends results to LLM
-   Generates executive strategy memo

------------------------------------------------------------------------

# 💬 CLI Interface

Run inside Databricks:

start_chatbot()

Example:

You: Simulate supply shortage of 15 percent\
Assistant: Executive Summary + Revenue Impact + Strategy Recommendation

------------------------------------------------------------------------

# 🧪 Testing Framework

Includes:

-   Table validation tests
-   Schema validation
-   Simulation logic validation
-   Agent routing validation
-   LLM response checks

------------------------------------------------------------------------

# 🛠 Technologies Used

-   Python
-   PySpark
-   Databricks Free Edition
-   Databricks GPT OSS
-   Regex-based tool routing

------------------------------------------------------------------------

# 🎯 Business Value

-   Automated decision support
-   Rapid scenario evaluation
-   AI-generated executive reporting
-   Reduced manual analytics effort

------------------------------------------------------------------------

# 🌟 Final Note

This project demonstrates how GenAI + Agentic AI + Simulation + Data
Engineering can combine to create a real-world intelligent business
decision system.
