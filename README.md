# AI Mentor Bootcamp — P. D. S. Aravind Kumar
Public portfolio of 12-day AI Trainer Workshop. By Day 12: 6 daily notebooks + capstone Streamlit URL.

## Day 1 — Setup complete
- Google AI Studio API key provisioned
- Groq API key provisioned
- Hello-Gemini call working — see [Day1_Setup.ipynb](Day1_setup.ipynb)
- <img width="1905" height="790" alt="image" src="https://github.com/user-attachments/assets/b2a62205-27d6-4695-a785-cc0083b54e90" />

- 4-tool comparison matrix from Lab 1A: see screenshot below
<img width="886" height="563" alt="image" src="https://github.com/user-attachments/assets/cdfa0073-12bf-4026-a3c8-d34539fd8ade" />
## Day 2 Lab 2B — Errors handled
 1. **Markdown fence wrapping** (`\`\`\`json ... \`\`\``)
The retry prompt asks Gemini to output raw JSON without fences. Triggers on ~5-10% of calls.
 2. **Hallucinated phone number when source has none**
`Optional[str] = None` in Pydantic — model returns `null`, schema validates.
 3. **Empty / whitespace-only input**
Pydantic raises ValidationError with "Field required". Caller catches.
 ## Sample résumés processed: 3 / 3 successful

