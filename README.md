# Autonomous Investment Research Agent

##  Problem Statement

Investors spend significant time manually researching companies before making investment decisions. They need to analyze financial reports, market conditions, competitors, and public sentiment from multiple sources, which can be time-consuming and complex.

## Solution

This project uses an autonomous AI agent that performs company research automatically. The user provides a company name, and the agent gathers relevant information, analyzes the data using AI, and generates an investment research summary.

## How It Works

1. User enters a company name.

Example:
Analyze Tesla

2. The AI agent collects information from multiple sources:

- Financial reports
- Latest company news
- Market trends
- Competitor analysis
- Social media sentiment
- Industry insights

3. The AI analyzes the collected data and generates:

- Company performance score
- Growth potential
- Risk factors
- Market position
- Investment recommendation

##  Features

### Automated Company Research
- Collects information about a company from different data sources.
- Reduces manual research time.

### Company Evaluation
- Analyzes financial and market factors.
- Generates an overall company score.

###  Growth Analysis
- Identifies growth opportunities based on market trends and company performance.

### Risk Identification
- Detects potential risks such as:
  - Competition
  - Market changes
  - Financial challenges

### AI-Based Recommendation
- Provides an investment summary based on collected insights.

##  Example Output
Company: Tesla

Company Score:
8/10

Growth:
High

Strengths:

Strong EV market presence
Advanced technology

Risks:

Increasing competition
Market volatility

Recommendation:
Further Analysis Needed


##  Tech Stack

### AI Agent Framework
- LangChain / LangGraph / CrewAI

### Large Language Model
- Google Gemini API

### Data Collection
- Financial APIs
- News APIs
- Market Data APIs
- Web Search APIs (Tavily / Google Search API)

### Knowledge Retrieval
- RAG Architecture
- Vector Database:
  - ChromaDB
    
### Backend
- Python
- FastAPI / Flask

### Frontend
- Streamlit

## Applications

- Individual investor research
- Stock market analysis assistance
- Financial advisory support
- Portfolio research automation
- Market intelligence

## Future Enhancements

- Real-time stock price monitoring
- Portfolio analysis
- Automated investment alerts
- Multiple company comparison
- AI-generated financial reports
- Personalized investment strategies

##  Objective

The goal of this project is to build an autonomous AI investment research assistant that simplifies company analysis by collecting information, identifying important insights, and helping investors make informed decisions through AI-generated reports.

