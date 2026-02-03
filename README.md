# Capstone-Project-AI-Tools-and-Trends-
From AI Tools to Trends: An analysis of Pre and Post Chatgpt Boom in AI usage and the challenges and solutions in selecting AI tools

## AI Tools Market Analysis & Opportunity Dashboard

A data-driven dashboard that analyzes the AI tools ecosystem, measures market demand, and highlights opportunity spaces for new AI products.
This project collects, processes, and visualizes data from multiple online platforms to understand how users discover, discuss, and adopt AI tools.

## Project Overview

The AI boom has created massive growth — but also overwhelming choice.
Thousands of tools are being launched, yet founders and creators struggle to understand what people actually want.

This dashboard provides:

A consolidated dataset of AI tools and trends

Search + launch trends from major platforms

Insights into gaps and opportunities in the market

Visualizations that reveal user demand and tool saturation

Built for researchers, founders, and creators looking to design meaningful AI products.

## Key Features

Interactive dashboard for exploring trends

Market demand analysis using Google Trends

Launch activity from Product Hunt

User interest from YouTube search/view metrics

Tool indexing from GitHub, FutureTools, and TAAFT

Comparisons across platforms

Category-level saturation & opportunity mapping

## Data Sources & Collection Methods
Source	                              Method	             Tools/Libraries	
YouTube	                         YouTube Data API v3	    googleapiclient	
Product Hunt	                     GraphQL API	          requests	
Google Trends	                    PyTrends library	      pytrends	 
GitHub	                          API + parsing	          requests, base64
FutureTools	                      Web scraping	          BeautifulSoup, requests	
There's An AI For That (TAAFT)   Selenium scraping	      selenium, BeautifulSoup	

All datasets were cleaned, merged, and normalized for consistent analysis.

## Tech Stack

Python

Pandas / NumPy

BeautifulSoup / Selenium

Requests

PyTrends

Matplotlib / Seaborn / Plotly

Streamlit or Jupyter Notebook (depending on your setup)
