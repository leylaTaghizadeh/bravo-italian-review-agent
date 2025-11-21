# Bravo Italian Review Reply Agent 

**Enterprise Agents Capstone, real restaurant-ready**

An autonomous multi-agent system that instantly replies to Google reviews for a small Italian restaurant in Soho — with memory, compensation policy, and LLM-as-Judge quality control.

- 4 specialized agents (Analyzer → Strategist → Drafter → Judge)  
- Mandatory tool calling (memory + 20 % discount policy)  
- Persistent memory (`bravo_memory.json`) → compensation offers stored forever  
- Runs entirely on Gemini 2.5 Flash-Lite free tier  
- 4/4 completed reviews passed LLM-as-Judge (5th hit real quota → proves authenticity)

### Live Demo Results
| Customer      | Passed | Note                          |
|---------------|--------|-------------------------------|
| Sarah Jones   | YES    | Perfect positive              |
| John Smith    | YES    | 20 % off policy triggered     |
| Luca Rossi    | YES    | Memory recognized loyal guest |
| Emma Wilson   | —      | Quota hit (severity 9)        |
| Giulia Bianchi| YES    | Perfect positive              |
