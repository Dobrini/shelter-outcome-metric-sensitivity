## Project Title

Sensitivity Analysis of Shelter Outcome Metrics Using Shelter Animals Count Data



## Project Overview

Animal shelter outcomes are often summarized using high-level outcomes such as adoption rate or live release rate. However, these metrics can vary substantially depending on how outcomes are defined, grouped, or excluded.



This project uses aggregated, non-identifiable data from **Shelter Animals Count (SAC)** to examine how sensitive commonly used shelter outcome metrics are to definitional choices. The analysis is methodological rather than evaluative and does not assess or rank individual shelters.



The goal is to demonstrate how metric construction alone can influence interpretation, even when the underlying data remain unchanged. 



## Data Source

Shelter Animals Count (SAC)

Years covered: 2023-2024

Data level: Aggregated shelter data only

No individual animals, people, or organizations are identifiable



All use and reporting complies with the Shelter Animals Count Data Use Agreement



## Research Objective

To assess how changes in outcome definitions affect commonly reported shelter metrics, with a focus on metric sensitivity rather than shelter performance. 



## Key Questions

How sensitive are commonly reported shelter outcome metrics to definitional choices?

How much do adoption rate and live release rate change when transfers are excluded?

Do small definitional changes meaningfully alter interpretation at an aggregate level?



## Primary Metric - Adoption Rate

Defined as:

		Adoption Rate = (Total Adoptions) / (Total Outcomes)



This metric is commonly used and easily interpretable, making it a useful baseline for sensitivity analysis. 



## Secondary Metric - Live Release Rate (LRR)

Live release rate is examined under multiple definitions to evaluate sensitivity to outcome inclusion or exclusion.

Baseline Definition:

	Live outcomes include: adoptions and returns to owner

	Terminal outcomes include: euthanasia and died in care

		Live Release Rate = (Adoptions + Returns to Owner) / (Total Outcomes)



## Sensitivity Analysis / Alternate Definitions

Alternate versions of both adoption rate and live release rate are calculated by modifying which outcome categories are included in the numerator and denominator. 



The analysis focuses on the excluding transfers from total outcomes, as transfer reporting can be operationally ambiguous or inconsistent across shelters. Baseline metrics are compared against alternate definitions to quantify how definitional choices affect reported values.



Observed differences are interpreted as evidence of metric sensitivity rather than as indicators of shelter effectiveness. 



## Methods and Tools

Initial data review and restructuring in spreadsheet software

Analysis conducted using:

	Python (pandas, matplotlib)




## Compliance and Ethics

All results are reported in aggregated form only.

No individual shelters, organizations, people, or animals are identified.

Results are framed neutrally and respectfully.

All visualizations and summaries include required SAC attribution language.



## Project Status

Complete. This repository presents a focused sensitivity analysis of shelter outcome metrics using SAC data.

