# Trip Budget Planner AI Agent

An AI agent (LangGraph + Google Gemini) that plans a trip and checks it against a budget.
The agent decides by itself which tools to call and combines their results.

## Tools
| Tool | What it does |
|---|---|
| get_weather | Live weather for a city (Open-Meteo) |
| convert_currency | Currency conversion (Frankfurter) |
| calculate | Safe calculator |
| estimate_trip_cost | Estimates total trip cost in INR (sample data) |
| check_budget | Compares the cost with the budget |
| packing_list | Suggests what to pack from the weather |

## How to run
1. Install Python 3.10+
2. Create and activate a virtual environment:
   ```
   python -m venv .venv
   .venv\Scripts\activate
   ```
   (Mac/Linux: `source .venv/bin/activate`)
3. Install packages: `pip install -r requirements.txt`
4. Get a free key from https://aistudio.google.com/apikey
5. Copy `.env.example` to `.env` and paste your key
6. Run: `python agent.py`

## Example questions
- Plan a 4-day standard trip to Goa for 3 people, travel fare Rs 2000 each. Budget is Rs 40000. What's the weather there?
- What if we go budget style instead?
- What should I pack for 3 days in Manali?

## Team
[-AFFAN ZOHEB -ENG25CS0234]
[-DHANUSH K -ENG25CS0239]
[-LN HARIHAR -ENG25CS0254]
[-N MANOJ -ENG25CS0262]
[-Nikhil Yadav-ENG25CSCS0266]
