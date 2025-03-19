# F1 Statistics Agent

A simple and efficient tool for Formula 1 enthusiasts that leverages AI and SQL to provide instant access to historical F1 race data and statistics. Perfect for enhancing your F1 viewing experience with real-time fact-checking and statistical analysis.

## Features

- Natural Language Query Processing: Ask questions about F1 statistics in plain English
- Comprehensive F1 Database: Access historical race and qualifying data
- AI-Powered Analysis: Utilizes Google's Gemini Pro model for intelligent query processing
- SQL-Based Data Retrieval: Efficient and accurate data fetching
- Real-time Results: Get instant answers during race discussions

## Technical Stack

- Python with Pandas for data processing
- SQLite database for data storage
- LangChain framework for AI integration
- Google Gemini Pro for natural language processing
- SQLAlchemy for database operations

## Installation

1. Clone the repository
2. Install required dependencies:
   ```bash
   pip install langchain langchain-experimental pymysql transformers accelerate langchain-google-genai pillow
   ```
3. Set up your Google API key for Gemini Pro access

## Usage

1. Load the Jupyter notebook `f1-agent.ipynb`
2. Configure your Google API key
3. Run the notebook cells to initialize the database and AI agent
4. Start querying F1 statistics using natural language

Example queries:
- "Who won the race in Spain 2019?"
- "How many races did Lewis Hamilton win?"
- "Show me qualifying results from Monaco 2018"

## Data Structure

The system uses two main tables:

### Race Table
- Position
- Driver Number
- Driver
- Driver Abbreviation
- Car
- Laps
- Time/Retired
- Points
- Year
- Location

### Qualifying Table
- Position
- Driver Number
- Driver
- Driver Abbreviation
- Car
- Q1, Q2, Q3 times
- Laps
- Year
- Location

## Contributing

Contributions are welcome! Feel free to submit pull requests or open issues for improvements and bug fixes.
# f1-statistics-agent
