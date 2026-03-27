# LLM-Economic-News-Summarizer
An automated data pipeline using LLM (Gemini 2.5) and DSPy for economic news extraction and sentiment analysis.

## Tech Stack
- Python 3.10+
- [DSPy](https://github.com/stanfordnlp/dspy) — structured LLM framework
- Google Gemini 2.5 Flash — language model via API
- pandas — data processing and table output
  
## What it does
- Input any economic news article as plain text
- AI pipeline extracts 5 structured fields per article:
  - **Summary** — concise 3–5 line overview
  - **Key Points** — bullet point breakdown of facts
  - **Insight** — economic impact or market implication
  - **Sentiment** — Positive / Negative / Neutral
  - **Tags** — category labels for filtering
- Processes multiple articles in batch → filterable DataFrame

## Example Output
<img width="1201" height="500" alt="Screenshot 2569-03-27 at 12 40 22" src="https://github.com/user-attachments/assets/287a0cdb-5da5-48b3-9f9e-b1c29001a71d" />
