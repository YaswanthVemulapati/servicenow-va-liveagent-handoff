# 🚀 ServiceNow Virtual Agent → Live Agent Handoff

## Project Overview
A complete customer support automation built on ServiceNow PDI.
Virtual Agent collects issue details, creates an Incident, and 
seamlessly hands off to a Live Agent via AWA Chat Queue.

## Flow
User → Virtual Agent → Incident Created → Chat Queue → Live Agent

## Tech Stack
- ServiceNow Virtual Agent Designer
- Advanced Work Assignment (AWA)
- Website Support Queue
- Agent Workspace

## Key Script
```javascript
vaVars.LiveAgent_queue = 'Website Support Queue';
vaSystem.connectToAgent();
```

## Screenshots
[Add your screenshots here]

## Next Goal
WhatsApp Integration with ServiceNow Virtual Agent
