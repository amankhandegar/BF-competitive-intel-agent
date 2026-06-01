# BigFix Competitive Intelligence Agent
### AI-powered competitor monitoring for BigFix Compliance PM

## What this does
Automatically monitors Tanium, Ivanti, and ManageEngine 
every Monday at 8am. Pulls data from RSS feeds and NewsAPI, 
analyses it with Google Gemini AI, and delivers a structured 
PM-grade competitive brief to Google Sheets — fully automated, 
zero manual effort.

## How it works
1. Schedule Trigger fires every Monday 8am
2. Fetches articles from 6 RSS sources + NewsAPI simultaneously
3. Normalises and filters to last 7 days only
4. Sends all articles to Google Gemini with PM-specific instructions
5. Gemini produces structured brief with threat levels and actions
6. Results logged automatically to Google Sheets

## Output includes
- Executive summary across all 3 competitors
- Key signals rated High Threat / Watch / Opportunity
- BigFix implications and recommended PM actions
- Weekly competitor comparison side-by-side
- Feature gaps and differentiation opportunities

## Tech stack
- n8n (workflow automation)
- Google Gemini 1.5 Flash (AI analysis)
- NewsAPI (news aggregation)
- Google Sheets (output storage)

## Files
- `bigfix_competitive_intel.json` — import this into n8n to run the workflow

## Built by
Aman Khandegar — Product Manager, BigFix Compliance  
Built as a practical AI demonstration of competitive intelligence automation
