---
layout: post
title: Unscrambl Drive - Real-Time Event Detection for a Hyper-Connected World
date: 2023-07-01 21:01:00
description: Unscrambl Drive - Real-Time Event Detection for a Hyper-Connected World
tags: unscrambl
categories: Product
featured: false
---

In today's fast-paced industries, data-driven decisions must often be made in seconds—or even milliseconds. From telecommunications and banking to healthcare and aviation, the need for real-time insights is paramount. At Unscrambl, we tackled this challenge head-on by developing a flagship product, Unscrambl Drive, an advanced real-time event detection engine designed to turn complex, high-volume data streams into actionable intelligence.

## The Power of Real-Time Insights Across Industries
Unscrambl Drive was purpose-built to address the demands of diverse sectors:

- Telecommunications: Imagine processing millions of DPI (Deep Packet Inspection) records every second to detect the perfect moment for sending a personalized SMS offer. Drive makes this possible by identifying ideal engagement opportunities based on real-time user activity.
- Banking: Financial transactions demand both speed and accuracy. Drive can process streams of credit card records in sub-second latency, enabling instant push notifications to customers’ mobile apps for improved engagement and fraud prevention.
- Healthcare: In medical environments, Drive’s ability to integrate data from bedside monitors and electronic medical records (EMR) enables early detection of critical conditions, like sepsis, by predicting adverse events based on real-time physiological data.
- Aviation: Airports handle an overwhelming amount of data from air traffic, gate assignments, and passenger manifests. Drive helps duty managers handle this deluge, providing decision support that factors in real-time changes and potential repercussions, from minimizing passenger delays to optimizing gate usage.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/drive-banking.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/drive-healthcare.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/drive-aviation.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>

## Building a Real-Time Engine with Precision and Scalability
Drive's underlying architecture was designed to process billions of records daily, all with sub-second latency. It achieves this through several key capabilities:

- Data Enrichment: Enriching data in-flight, Drive can, for example, retrieve a cell tower’s latitude and longitude from a cell ID or normalize phone numbers into a standard format. Such enrichment empowers stakeholders with contextually rich data for better decision-making.

- In-Flight Data Manipulation: Manipulating data as it streams through Drive, we can convert or calculate new attributes—such as deriving merchant categories from MCC (merchant category code) in credit card data.

- Real-Time Aggregation and Model Scoring: Drive can maintain rolling aggregates, like the average heart rate over the last 10 minutes, and perform real-time ML model scoring for predictive insights (e.g., predicting the likelihood of a passenger missing their flight).

- Trigger, Alert, and Event Generation: This enriched data feeds into Drive’s logical reasoning engine, enabling it to generate contextual triggers and alerts tailored to specific use cases.

## An Intuitive Configuration Experience with Mad-Libs
A standout feature of Drive is its Mad-Libs-style configuration interface. End-users could craft triggers, alerts, and events with ease, using domain-specific language without grappling with cryptic data attributes. Each deployment could even expand this vocabulary, empowering non-technical users to customize their configurations.

## Real-World Impact: Deployments Across Global Organizations
Our team was proud to see Drive deployed across several high-profile organizations:

- Etisalat UAE: Enabled real-time processing of user data, providing timely marketing engagements and optimizing network usage.
- RCBC Bank, Philippines: Enhanced customer engagement by analyzing credit card transactions in real-time and sending personalized offers.
- Emory University Hospital (research setting): Supported healthcare professionals with predictive insights on patient outcomes.
- SATS, Singapore: Assisted duty managers in managing airport operations, improving efficiency by dynamically responding to real-time changes.


## Update: Post Unscrambl's Acquisition
Now with a much larger Global SI, Drive will probably see much more widespread deployment and adoption. While it has already proven itself as a powerful solution across industries, the need for real-time event detection continues to grow. As industries become more interconnected, Drive’s capabilities can transform how businesses operate and serve their customers in real time.