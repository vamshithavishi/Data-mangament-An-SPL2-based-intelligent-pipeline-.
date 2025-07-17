# Smart Log Reduction & Metrics Conversion Pipeline for Firewall Logs  
**Track:** Splunk Build-a-thon 2025 – Track 3: Data Management (SPL2 Pipelines)

## 🔍 Problem Statement  
Security Operation Centers (SOCs) face overwhelming volumes of firewall logs that lead to high storage costs, delayed threat detection, and inefficient alerting.

## 💡 Solution Overview  
Our SPL2-based intelligent pipeline performs:
- 🔁 **Log Deduplication**
- 🔎 **Filtering of Irrelevant Events**
- 📊 **Conversion of Logs to Metrics (L2M)**
- 🚨 **Real-Time Alerting for SOC Teams**

This reduces log volume by up to **90%** while improving detection and visibility in near real-time.

## ⚙️ Features
- 🔹 **SPL2 Pipeline** for efficient log parsing and transformation.
- 🔹 **Metric Generation** from firewall logs.
- 🔹 **Alert Triggers** based on customized thresholds.
- 🔹 **Architecture supports edge data reduction.**

## 🧪 How It Works
The SPL2 script:
1. Ingests firewall logs.
2. Applies deduplication rules.
3. Filters non-critical data.
4. Converts structured log events into metrics.
5. Routes metrics for real-time visualization and alerting.

> 🔧 See: [`spl2_pipeline.spl2`](./spl2_pipeline.spl2)

