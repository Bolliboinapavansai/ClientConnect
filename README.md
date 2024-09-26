# CareerMatchMailer

**CareerMatchMailer** is an AI-powered tool that extracts job listings from company careers pages and generates personalized cold emails. The tool uses Groq, Langchain, and Streamlit to generate cold emails, including relevant candidate portfolio links sourced from a vector database, based on specific job descriptions. This solution streamlines the outreach process for recruitment and business development, making it easier for companies to target potential clients or partners.

## Features

- Extract job listings from a company's careers page.
- Automatically generate personalized cold emails based on job descriptions.
- Attach relevant portfolio links based on vector database lookups.
- Provide a simple, user-friendly interface for non-technical users.

## Architecture

![WhatsApp Image 2024-09-26 at 10 27 07 AM](https://github.com/user-attachments/assets/03a4d747-68ed-4ff1-8075-120c7faf4030)


## Technical Stack

- **Groq API**: Powers the language model for generating personalized cold emails based on job descriptions.
- **Langchain**: Manages the orchestration of the language model and external data sources.
- **Streamlit**: Provides the UI for users to input company careers pages and view generated cold emails.
- **Vector Database**: Stores and retrieves candidate portfolios, ensuring personalized email content.
- **Python**: Back-end logic for coordinating job listing extraction and API interactions.


## Setup Instructions

To get started with **CareerMatchMailer**, follow these steps:



### Prerequisites
- Get an API key from [Groq API](https://console.groq.com/keys)
- Set up a `.env` file in the `app/` directory with your Groq API key:
  
