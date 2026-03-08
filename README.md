# 🧠✍️

**The most thorough AI text humanizer skill for Claude, ChatGPT, and any LLM.**

Upload one file. Get human-sounding output every time.

[![GitHub Stars](https://img.shields.io/github/stars/your-username/?style=flat-square)](https://github.com/your-username/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](LICENSE)
[![Works with Claude](https://img.shields.io/badge/Works%20with-Claude-orange?style=flat-square)](https://claude.ai)
[![Works with ChatGPT](https://img.shields.io/badge/Works%20with-ChatGPT-green?style=flat-square)](https://chat.openai.com)

---

## What It Does

This is a **drop-in skill file** (`SKILL.md`) that transforms AI-generated text into writing that sounds like a real human wrote it not just synonym-swapped, but **structurally and stylistically rewritten**.

It runs a **3-pass pipeline** + a final AI Audit:

1. **Pattern Extermination** strips 50+ known AI vocabulary/structural fingerprints
2. **Human Texture Injection** adds rhythm variation, real opinions, imperfection, specificity
3. **Flow & Coherence Rebuild** natural transitions, varied paragraph lengths, real endings
4. **AI Audit** a final pass asking "what still screams AI?" and fixing it

No app to install. No API key. No subscription. Just one Markdown file.

---

## Quick Start

### Option 1 Upload to Claude or ChatGPT
1. [Download SKILL.md](SKILL.md)
2. Upload it in any new chat with Claude or ChatGPT
3. Say: **`Humanize this:`** followed by your text

### Option 2 Clone and Use Locally (Claude Code)
```bash
git clone https://github.com/your-username/your-repo.git
cp your-repo/SKILL.md ~/.claude/skills/advanced-ai-writing-humanizer.md
```

### Option 3 Download the ZIP
⬇ Download ZIP → extract → upload `SKILL.md` to your AI chat

---

## Usage

```
Humanize this:
[paste your AI-generated text here]
```

**With tone modes:**

| Command | Result |
|---------|--------|
| `Humanize this [casual]:` | Relaxed, conversational |
| `Humanize this [formal]:` | Professional, but human |
| `Humanize this [academic]:` | Scholarly, no buzzwords |
| `Humanize this [preserve-length]:` | Match original word count |
| `Humanize this [aggressive]:` | Maximum transformation |

---

## Why This Is Different

Most humanizers do one thing: swap words with synonyms or rephrase sentences. They don't understand *why* AI writing feels robotic.

It goes deeper:

| Feature | Most Humanizers | This Skill |
|---------|----------------|-------------|
| Synonym replacement | ✅ | ✅ |
| AI buzzword removal | ✅ | ✅ |
| Structural pattern removal | ❌ | ✅ |
| Sentence rhythm variation | ❌ | ✅ |
| Voice/opinion injection | ❌ | ✅ |
| Controlled imperfection | ❌ | ✅ |
| Specificity audit | ❌ | ✅ |
| 3-pass pipeline | ❌ | ✅ |
| Final AI audit pass | ❌ | ✅ |
| Tone modes | ❌ | ✅ |
| Works with ANY LLM chat | ✅ | ✅ |

---

## Before & After Example

**Before (AI-generated):**
> In today's rapidly evolving technological landscape, artificial intelligence serves as a testament to human ingenuity. It is worth noting that AI has played a pivotal role in transforming industries across the globe, fostering innovation and facilitating unprecedented levels of efficiency.

**After (Humanized):**
> AI has changed how most industries operate, faster than most people expected. The efficiency gains are real. What's less clear is whether companies rushing to "leverage AI" actually know what problem they're solving, or whether they're just afraid of falling behind.

---

## What Gets Humanized

- Blog posts and articles
- Academic essays and reports
- Marketing copy
- Emails and business writing
- Social media captions
- Product descriptions
- README files (meta, we know)
- Code comments

## What Stays Intact

- Factual content and data
- Technical terms
- Quoted text
- Code blocks and formulas
- Intentional stylistic choices

---

## The Pattern Library

This skill targets 50+ known AI writing patterns across four categories:

- **Hollow inflation words** (serves as, underscores, pivotal, transformative...)
- **Structural AI tells** (bullet-point essays, bold headers, First/Second/Third...)
- **Punctuation fingerprints** (em dash overuse, semicolon stacking...)
- **Vocabulary fingerprints** (tapestry, realm, foster, leverage, robust...)

Full list in [SKILL.md](SKILL.md).

---

## Research Basis

This skill was built from:
- Wikipedia's [*Signs of AI writing*](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing) guide (WikiProject AI Cleanup)
- Copyleaks stylistic fingerprint research on LLM outputs
- Academic research on statistical properties of LLM-generated text
- Community observations across thousands of AI text samples

---

## Contributing

Found a new AI pattern? Spotted a word that's crept into the vocabulary?

1. Fork the repo
2. Add your pattern to the appropriate section in `SKILL.md`
3. Include a before/after example
4. Open a Pull Request

---

## Roadmap

- [ ] Language variants (British English, Spanish, French)
- [ ] Domain-specific modes (legal, medical, technical)
- [ ] GPT system prompt version (`SYSTEM_PROMPT.md`)
- [ ] Claude project instructions version
- [ ] Detection score estimator (rate your text 0–100)
- [ ] VS Code extension

---

## License

MIT free to use, modify, and distribute. Attribution appreciated.

---

## Topics

`ai-humanizer` `humanize-ai` `ai-writing` `ai-detection` `undetectable-ai` `claude-skill` `chatgpt-prompt` `prompt-engineering` `ai-text` `writing-tools` `content-creation` `ai-content` `llm` `anthropic` `claude-code-skill`

---

*If this skill helped you, consider giving it a ⭐; it helps others find it.*
