# Customer Segmentation using RFM Analysis

## Introduction

**Customer segmentation** is the process of segregating customers into various distinct groups, each with their own set of common characteristics.

**RFM Analysis** is an effective method used to segment customers based on their overall value to the company. The three dimensions in RFM stand for:

- **Recency**: *When was the last time the customer made a purchase?*
- **Frequency**: *How often does the customer make a purchase?*
- **Monetary value**: *How much does the customer spend?*

## Business Problem

In today's digital age when customers are getting more and more sophisticated and have much more options, it is no longer effective to employ a one-size-fits-all marketing strategy. Customers demand personalised attention towards their needs, and companies have to adapt their marketing approach in order to keep up with their competition and drive conversions.

By segmenting customers based on their RFM attributes and understanding their purchase behaviour, brands would be able to effectively target specific groups of customers with marketing communications that are much more relevant to their behaviour. This helps to boost customer loyalty and retention, maximise customer satisfaction and drive conversions.

## Executive Summary

After performing k-means clustering using RFM analysis, we are able to segment the customers into four distinct clusters:

| Cluster | No. of Customers | Recency | Frequency | Monetary Value | Customers' Characteristics | Value to Company |
| --- | --- | --- | --- | --- | :- | :- |
| 1 | 3,145 | 59 | 9 | 4,710 | High & frequent spenders | Highest value |
| 3 | 1,110 | 434 | 3 | 1,029 | Relatively inactive spenders | Second lowest value |
| 2 | 986 | 235 | 4 | 1,413 | Relatively recent spenders | Second highest value |
| 0 | 637 | 644 | 2 | 619 | Inactive & low spenders | Lowest value |

With this information, brands would be able to effectively target each group with marketing communications that are much more relevant to their behaviour, and spend more time and effort on retaining customers that generate higher value to them.
