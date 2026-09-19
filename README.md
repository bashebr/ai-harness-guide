# AI Harness Guide

A practical reference for the **bare model vs. harness** architecture — how production LLM systems split inference from application logic.

**Live site:** enable GitHub Pages (see below) and visit `https://<username>.github.io/ai-harness-guide/`

## What's inside

- Core paradigm and mental models
- Comparison table (state, tools, safety, observability)
- Tool-calling loop explained step by step
- Minimal Python harness blueprint
- Production checklist and anti-patterns
- Links to official docs (OpenAI, Anthropic, MCP)

## Deploy to GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Choose branch **`main`** (or `master`) and folder **`/ (root)`**.
5. Save. The site will be live in ~1 minute at your Pages URL.

No build step required — `index.html` is served as static content.

## Local preview

```bash
python3 -m http.server 8080
```

Open [http://localhost:8080](http://localhost:8080).

## License

Documentation is provided as-is for educational use.
