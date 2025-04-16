# Insurance Claims Agentic System

An AI-powered system for streamlining and automating the insurance claims process, providing fraud detection, and enhancing the user experience for both claimants and insurance staff.

## Project Structure

```python
insurance_claims_system/
├── README.md
├── requirements.txt
├── app.py                  # Main Streamlit application entry point
├── data/
│   ├── init_db.py          # Database initialization script
│   └── mock_data.py        # Script to generate mock data
├── agents/
│   ├── __init__.py
│   ├── orchestrator.py     # Agent Orchestrator implementation
│   ├── claim_agent.py      # Claim Processing Agent
│   ├── fraud_agent.py      # Fraud Detection Agent
│   └── document_agent.py   # Document Management Agent
├── models/
│   ├── __init__.py
│   ├── user.py             # User model
│   ├── claim.py            # Claim model
│   ├── document.py         # Document model
│   └── fraud_detection.py  # Fraud detection model
├── utils/
│   ├── __init__.py
│   ├── db.py               # Database utilities
│   ├── auth.py             # Authentication utilities
│   ├── validation.py       # Data validation utilities
│   └── visualization.py    # Data visualization utilities
├── ui/
│   ├── __init__.py
│   ├── pages/
│   │   ├── __init__.py
│   │   ├── home.py         # Home page
│   │   ├── submit_claim.py # Claim submission page
│   │   ├── view_claims.py  # Claims viewing page
│   │   ├── admin.py        # Admin dashboard
│   │   └── adjuster.py     # Adjuster dashboard
│   └── components/
│       ├── __init__.py
│       ├── claim_form.py   # Claim form component
│       ├── document_upload.py # Document upload component
│       ├── claim_status.py # Claim status display component
│       └── dashboard.py    # Dashboard components
└── tests/
    ├── __init__.py
    ├── test_agents.py
    ├── test_models.py
    └── test_ui.py
```
