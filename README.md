- Auto-Learning Assistant in Google Sheets

An intelligent Google Sheets automation powered by APIs — auto-fetches top resources, generates beginner-friendly summaries, and updates everything in real-time inside your Sheet.

- Features

- **No UI or browser switching**
- Just type a topic in the first column — let automation do the rest
- Fetches top learning resources using **Perplexity API**
- Summarizes each topic with **DeepSeek API**
- Real-time, in-sheet updates — no refresh or scripting needed

- Tech Stack

- [n8n](https://n8n.io/)
- [Google Sheets API](https://developers.google.com/sheets/api)
- [Perplexity API](https://www.perplexity.ai/)
- [DeepSeek API](https://deepseek.com/)
- [OpenAI (optional for formatting or explanations)](https://platform.openai.com/)

- How It Works

1. User types a topic into **Column A** of the Google Sheet.
2. n8n automation:
   - Triggers on new input.
   - Calls Perplexity API to get best 3–5 curated resources.
   - Sends the topic to DeepSeek to generate a beginner-friendly explanation.
   - Updates **Column B** with the explanation, **Column C** with resource links.
3. All updates happen seamlessly in your Sheet.

- Use Cases

- Rapid topic revision
- Daily study prompts
- Auto-curated notes
- Research prep for students or professionals

- Setup Instructions

> You’ll need:
> - An n8n instance (self-hosted or cloud)
> - Google Sheets API access
> - Perplexity + DeepSeek API keys

1. Clone the [automation template] or import the n8n JSON workflow.
2. Add credentials for:
   - Google Sheets (OAuth2)
   - Perplexity API
   - DeepSeek API
3. Configure the Google Sheet ID, worksheet name, and columns.
4. Turn on your workflow in n8n.
5. Start typing in the sheet!

- Real-World Impact

Crossed **1000+ connections** already — a sign of how tiny tools, built right, can scale knowledge access and productivity. No need for dashboards. Just a single sheet, supercharged by AI.

---

- Feedback & Contributions

This is just the start — feel free to fork, customize, or build on top. If you have suggestions or want to collaborate, open an issue or reach out!

