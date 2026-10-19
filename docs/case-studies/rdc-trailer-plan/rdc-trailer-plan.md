# RDC Trailer Plan
## Case Study: Enterprise Analytics Application
### Executive Summary

The RDC Trailer Plan is an enterprise supply chain analytics platform I designed and built to track Regional Distribution Center (RDC) to Store trailer deliveries. This application directly supports the company's Plan Compliance goal by providing visibility into whether RDCs are shipping the right number of trailers to stores at the right times.

### Key Outcomes:
- 3,700+ lines of production SQL orchestrating 20+ source tables
- 11-view Tableau dashboard with 78,000+ total views
- 1,000+ unique active users across the enterprise
- ~200 daily views at peak adoption
- ~50 features delivered in 6-month development cycle
- <0.1% data quality issues through multi-source fallback design

### Business Context
#### The Problem
The company needed to measure and improve how distribution centers deliver trailers to stores. The key questions:
- Are stores receiving the planned number of trailers each day?
- When trailers are over or under plan, who owns the issue?
- How do we track carry-overs, pull-forwards, and utilization?

No existing system provided this visibility at the level of granularity needed for operational decisions.

#### The Goal
Achieve enterprise Plan Compliance target - the percentage of store-days where actual trailer deliveries match the planned count.

#### The Stakeholders
Role | Use Case
---- | ----
Flow Planning | Daily operational decisions, capacity planning
Transportation Offices | Route optimization, driver scheduling
Regional DC Operations | Preformance tracking, compliance monitoring
Enterprise Analytics | Report integration
Weekly Report Recipients | Business intelligence and trend analysis
