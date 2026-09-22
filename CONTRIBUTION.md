# My Role in Ulavan Connect

## What I Built

1. **Gemini AI Query Pipeline**
   - Designed prompt structure for market-data analysis
   - Implemented few-shot prompting for price-gap explanation
   - Built fallback logic for low-confidence queries

2. **FastAPI Backend**
   - Created `/verify-price` endpoint
   - Implemented rate limiting and request validation
   - Built error handling for missing market data

3. **WhatsApp Integration**
   - Connected webhook to receive farmer queries
   - Designed message formatting for feature phones
   - Built response formatting for clarity

## What I Didn't Build

- Frontend/UI dashboard (team member 2)
- Government data API wrapper (team member 3)
- Database schema and ORM (team member 1)

## Why This Matters

Most hackathon projects fail at deployment. We won "Most Deployable" because each component was designed to work in isolation—my API could handle missing data, my prompts had fallbacks, and my error messages guided farmers even when systems degraded.
