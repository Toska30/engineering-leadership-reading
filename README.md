# Engineering Leadership Reading

A small, curated reading list I keep coming back to. Two themes:

1. **AI in engineering teams** — how teams actually integrate LLMs and agentic tooling into delivery, without losing ownership of their work.
2. **Engineering leadership in regulated software** — what changes when "done" includes audit-readiness and traceability.

This is opinionated. The list is short on purpose. If something falls off this list, it means I no longer think it's load-bearing.

---

## AI in engineering teams

### Books

- **"AI Engineering" — Chip Huyen** *(2025)*
  The first practical book I've read on building software *with* LLMs as components, not just calling APIs. Strong on evaluation and on when AI is the wrong tool. Read the chapter on guardrails twice.

- **"Designing Machine Learning Systems" — Chip Huyen** *(2022)*
  Older, but the systems-thinking carries over. The chapter on monitoring and feedback loops is what I refer back to when teams ask "how do we know if the AI is still working?"

### Articles & posts

- **"Building effective agents" — Anthropic** *(2024)*
  The clearest framing I've seen for when to reach for an agent vs a simple chain. Most teams over-complicate; this post gives you the vocabulary to push back.

- **"Sparking innovation: how AI-driven engineering boosts developer productivity" — various**
  Useful as a survey of what's been tried. Take the productivity numbers with skepticism; take the workflow patterns seriously.

- **Simon Willison's blog**
  Not a single post — the running blog. Best practical thinking I know of on what actually works with LLMs in day-to-day developer workflows.

### Tools worth understanding (not endorsing)

- **n8n** — visual workflow builder. Good for prototyping AI-augmented internal tooling fast.
- **LangChain / LlamaIndex** — useful to know the abstractions even if you choose not to use them.
- **Ollama** — local LLMs. Indispensable when client data can't leave the environment.

---

## Engineering leadership in regulated software

### Books

- **"An Elegant Puzzle" — Will Larson**
  Best general engineering management book I know. The chapter on team size and structure is what I think about when I'm asked "how big should this team be?"

- **"The Manager's Path" — Camille Fournier**
  For anyone moving from senior engineer to first-line manager. Honest about the loss of technical depth that comes with the transition.

- **"Accelerate" — Forsgren, Humble, Kim**
  The DORA metrics. Most useful in regulated contexts because it gives you data to push back when compliance functions ask for slower, more careful delivery — you can show *with evidence* that faster + safer is possible.

### Standards worth reading (excerpted, not cover to cover)

- **IEC 62304** — medical device software lifecycle. Even outside medical, the structure is worth understanding.
- **ISO 13485** — quality management for medical devices.
- **EU MDR** — Medical Device Regulation. The annexes are where the work lives.
- **EU AI Act** *(2024)* — relevant for anyone deploying AI features in healthcare, finance, HR.

### Articles & posts

- **"The unreasonable effectiveness of having a regulatory expert on your team" — various**
  The point: hire someone who *knows* the regulation. Don't expect engineers to learn it from PDFs.

- **LeadDev archives**
  Search the conference archive — strong material on engineering management in regulated industries (fintech, healthtech). Worth an evening.

---

## What's deliberately *not* on this list

- Generic "10 habits of senior engineers" listicles
- AI hype posts that don't ship anything
- Books about scaling Google — useful for Google, distracting for a team of 8

---

## Author

Blerta Toska — utvecklingsledare och linjechef, Malmö.
[LinkedIn](https://www.linkedin.com/in/blerta-toska)
