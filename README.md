# NGER-CER-ABS-data-engineering-and-analysis

## Project Overview
<p>This project analyses 10 years of Australian energy production, emissions, and urban development trends by integrating multiple government datasets. The goal is to start with simple visual analytics and progressively build towards policy-relevant, high-impact insights that connect electricity generation, carbon emissions, and construction growth.</p>
<br>
<p>The project is designed to evolve from descriptive analysis into strategic and predictive insights.</p>

## Project Objectives
<li>Analyse long-term trends in electricity production and CO₂ emissions</li>
<li>Understand how energy infrastructure aligns with urban and construction growth</li>
<li>Evaluate the impact of energy projects and accreditations</li>
<li>Create an interactive analytical framework that can scale into forecasting and scenario analysis</li>

## Data used
<p>This project integrates the following datasets:</p>
<li>NGER (National Greenhouse and Energy Reporting) Data</li>
<li>Clean Energy Regulator (CER) Data</li>
<li>Australian Bureau of Statistics (ABS) Data</li>

## Data integration
<p>The datasets are linked using:</p>
<li>facility_name_norm (CER ↔ NGER)</li>
<li>State (NGER ↔ ABS)</li>
<li>Financial years derived from source_dataset_id</li>
<br>
<p>Special care is taken to handle granularity differences between facility-level and state-level data to avoid double counting.</p>

## Tools and Technologies used
<img src = "https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white" /> <img src = "https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white"/> <img src = "https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" /> <img src = "https://img.shields.io/badge/Microsoft_Word-2B579A?style=for-the-badge&logo=microsoft-word&logoColor=white" /> <img src = "https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue"> <img src = "https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white" />

## Why does this project matter?
<p>Energy infrastructure, emissions reduction, and urban development are deeply interconnected. This project aims to bridge environmental data with economic and urban indicators, enabling:</p>
<li>Better infrastructure planning</li>
<li>Smarter emissions reduction strategies</li>
<li>Evidence-based policy discussions</li>
