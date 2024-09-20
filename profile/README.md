# Finanalize

## Description

A service that provides financial report for a given stock symbol.

## Workflow

1. User provides a stock symbol.
2. Service scrapes the internet for information about the stock. (maybe even provided documents)
3. Service analyzes the information.
4. Service provides a report.
5. User gets a preview of the report, and can choose to buy the full report.

## Technologies

- LLMs (for the report generation)
- Python (for the LLM inference)
- Rust or Go (for the backend)
- Svelte (for the frontend)
- RabbitMQ (for the message queue)

## Techniques

- Web Scraping
- RAG
