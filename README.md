# Spotify Streaming History Analysis

An interactive Power BI dashboard exploring personal Spotify listening history to uncover music preferences, listening patterns, and streaming trends.

## Project Overview

This project analyses my personal Spotify streaming history using Power BI. The dashboard transforms raw listening data into interactive visualisations, providing insights into listening habits, music preferences, and activity over time.

## Tools & Technologies

- Power BI
- Power Query
- DAX
- JSON

## Dataset

- **Source:** Personal Spotify Extended Streaming History
- **Time Period:** 2021–2026
- **Original Records:** 21,628
- **Records after cleaning:** 21,507

The dataset contains information about listening activity, including timestamps, track details, artists, albums, and streaming duration.

*Note: The dataset is based on personal listening history and is not included in this repository.Spotify users can request their own Extended Streaming History through Spotify's account privacy settings.*

## Data Preprocessing

The dataset was prepared before dashboard development.

Key preprocessing steps:

- Imported Spotify JSON files.
- Combined listening history records.
- Handled missing values.
- Removed 121 records with null track URIs.
- Cleaned track URI fields
- Prepared date and time fields for analysis.

## Dashboard Pages

The dashboard consists of three interactive pages:

### 1. Overview
Provides a summary of overall listening activity and key metrics.

### 2. Listening Patterns
Explores listening behaviour and trends across different time periods.

### 3. Details
Provides detailed information about listening activity, tracks, artists, and other streaming attributes.

## Key Features

- Interactive dashboard navigation.
- Listening trend analysis.
- Date-based filtering.
- Platform-based filtering.
- Track and artist-level exploration.
- Dynamic visualisations and DAX-based measures.

## Purpose

This project demonstrates practical skills in data cleaning, data modelling, DAX, data analysis, and interactive dashboard development using Power BI.

---

**Built with Power BI | Personal Data Analytics Project**