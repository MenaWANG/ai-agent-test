# ai-agent-test

This repo is based on my learning from the course [Learn AI Agents](https://www.coursera.org/learn/learn-ai-agents/home/welcome) by Scrimba on Coursera. 


## My Note


* Goal for the agent:
    * Build an agent that can get the current weather at my current location and give me some localized ideas of activities I can do.

* Commit 1: connect-to-llm
    * Basic set up to connect to and call `openai`
    * The question was asked directly to the LLM, which doesn't have access to my location and weather, the answer is therefore pretty generic.
    * We need to get LLM to interate over the query, utilize external tools where necessary, until it achieve a satisfactory answer.