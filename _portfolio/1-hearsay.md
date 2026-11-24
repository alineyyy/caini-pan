---
title: "HearSay — multi-agent fact-checking for administrative advice"
excerpt: "LLM agents that check the advice international students pass around against dated official French sources. Built at the AWS Agents for Humans hackathon, Sept 2026."
collection: portfolio
---

[Code on GitHub](https://github.com/alineyyy/Hearsay)

International students in France rely on advice from friends and forums, which is often out of date. HearSay takes what you heard, splits it into individually checkable claims, searches the official French corpus for each one, and returns a verdict (confirmed, outdated, partly true, not covered, contradicted) with the source document and the date it was last updated.

- Five-stage agent pipeline built with Strands Agents and Claude on Amazon Bedrock, with typed (Pydantic) contracts between stages.
- BM25 retrieval over ~5,500 official documents from service-public.fr; retrieval and date logic are deterministic, so every verdict traces back to a source.
- Multilingual: a planner agent rewrites questions written in Chinese, English or other languages into formal administrative French for retrieval, then answers in the user's language.
