BharatCred Python backend for credit scoring.

Request body is a JSON array of transactions with:
- description: string
- amount: number
- date: string

Example:
[
  {"description": "SALARY", "amount": 50000, "date": "2026-01-01"},
  {"description": "UPI PAYMENT", "amount": -1200, "date": "2026-01-03"}
]

Response contains:
- credit_score
- behavioral_insights
- ml_engine_diagnostics
- market_analysis
