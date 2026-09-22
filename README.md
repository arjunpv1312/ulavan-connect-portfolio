# Ulavan Connect — Portfolio Case Study

**Hackathon:** Tech for Good 2026  
**Award:** Most Deployable Project  
**Link to Original:** [Private repo owned by organizing team]

## Problem

Smallholder turmeric farmers negotiate prices without real-time market access. Traders often exploit information asymmetry.

## Solution

WhatsApp-based AI assistant that:
- Verifies trader offers against government market data
- Explains price gaps to farmers in local language
- Provides actionable negotiation points

## My Specific Contribution

### Core Development
- **Gemini AI Integration:** Built the prompt-chaining pipeline for market-data analysis and price verification
- **Backend Logic:** Developed the farmer-query parser and trader-offer validator in FastAPI
- **API Integration:** Connected WhatsApp API to FastAPI server with proper message queuing

### Key Code Responsibilities
- Query understanding module (NLTK + intent classification)
- Price-gap calculation and explanation generation
- Rate-limiting and error handling for production deployment

### Testing & Deployment
- Unit tests for price-verification logic
- Integration testing with WhatsApp staging API
- Deployment configuration for Google Cloud Run

## Tech Stack
- Python 3.11
- Gemini API (prompt engineering)
- FastAPI
- WhatsApp Cloud API
- Google Cloud (Cloud Run, Cloud Storage)
- NLTK
- Pandas (data processing)

## Architecture

[Insert architecture diagram showing your components]

## Code Samples

See `/code-snippets/` for representative examples of:
- Gemini API integration pattern
- Query processing flow
- Price verification logic

## Results
- ✅ Deployed to 50+ farmers in pilot
- ✅ Won Most Deployable Project (judged on working prototype)
- ✅ Planned for scaling to 5+ districts

## Note on Repository

This is a portfolio case study. The full source code is in the private hackathon repository owned by [Event Organizers]. This repository documents my individual contributions and architectural decisions for professional evaluation.

**Not included:** Code from other team members (backend integrations, database schemas, frontend components).

## How Recruiters Can Verify

- Check my GitHub commit history (if added as contributor)
- Review the team's project submission
- View the official project demo
- Contact [mentor/organizer name] for verification

---

**What I learned:** Building products that scale requires thinking in terms of MVP deployment, graceful degradation, and user safety—especially in agriculture tech where misinformation is costly.
