---
name: advanced-ai-writing-humanizer
description: Transforms AI-generated text into natural, human-sounding writing by removing patterns and injecting human texture.
---

# Advanced AI Writing Humanizer Skill

> Upload this file to Claude, ChatGPT, or any LLM chat interface. Once loaded, the AI will apply deep humanization to any text you paste.

---

## WHAT THIS SKILL DOES

When activated, this skill transforms AI-generated text into writing that reads, sounds, and feels like a real human wrote it not just by swapping words, but by restructuring thought patterns, injecting authentic voice, and eliminating every statistical fingerprint that modern AI detectors look for.

It runs a **3-pass rewrite pipeline** and a final **AI Audit** far deeper than a single-pass humanizer.

---

## HOW TO ACTIVATE

After uploading this file, simply say:

> **"Humanize this:"** followed by your text.

Optional modes:
- `"Humanize this [casual]:"` relaxed, conversational tone
- `"Humanize this [formal]:"` professional, but still human
- `"Humanize this [academic]:"` scholarly, avoids AI tells
- `"Humanize this [preserve-length]:"` keep roughly same word count
- `"Humanize this [aggressive]:"` maximum transformation

---

## THE 3-PASS PIPELINE

### PASS 1 PATTERN EXTERMINATION

Strip every known AI writing fingerprint:

**Hollow Inflation Words DELETE OR REPLACE**
- "serves as a testament to" → just state the thing
- "underscores the importance of" → say why it matters directly
- "it is worth noting that" → just note it
- "in today's rapidly evolving landscape" → meaningless; cut it
- "a crucial/pivotal/key role" → is it? prove it; if not, cut "crucial"
- "at the end of the day" → cut
- "it goes without saying" → then don't say it
- "needless to say" → cut
- "this highlights/showcases" → rewrite to show, not announce
- "delve into" → use "look at", "explore", "go through"
- "navigate" (metaphorical) → be specific: "handle", "deal with", "get through"
- "leverage" → use "use", "apply", "rely on"
- "utilize" → use "use"
- "facilitate" → use "help", "enable", "make easier"
- "robust" → be specific about what makes it strong
- "seamless" → describe the actual experience
- "cutting-edge" → say what's actually new about it
- "game-changer" → say how it changes things specifically
- "holistic" → describe the actual scope
- "synergy" → explain what actually combines well
- "moving forward" → cut or replace with timeline
- "going forward" → same
- "in conclusion" / "to summarize" → don't announce it; just end
- "it is important to note" → just note it
- "one must consider" → say who, and why
- "the fact that" → restructure sentence
- "in terms of" → be direct
- "with regard to" → be direct
- "moreover" / "furthermore" / "additionally" → cut or use "also"
- "notably" / "importantly" → cut

**Structural AI Tells DISMANTLE**
- No bullet-point essays unless bullets were in the source
- No bolded topic headers in every paragraph
- No "First... Second... Third... Finally..." skeleton
- No paragraph starting with a bolded summary of itself
- No "Let's explore X" / "Let's dive into X"
- No "Here's what you need to know:"
- No "Whether you're a... or a..., this guide is for you"
- No artificial balance: "On one hand... On the other hand..." when there's a clear answer
- No symmetrical three-part conclusions wrapping everything up neatly
- No transition sentences that exist only to transition: "With that in mind, let's turn to..."

**Punctuation Tells FIX**
- Em dashes (long dashes) used for "punch": replace with a comma, period, or rewrite
- Semicolons stacked in every paragraph: break into separate sentences
- Ellipsis for drama (...) : cut or rewrite
- Parenthetical asides in every paragraph: use sparingly

**Vocabulary Fingerprint ROTATE OUT**
These words appear at statistically higher rates in AI writing. Replace or remove:
- tapestry, mosaic, fabric (metaphorical)
- realm, sphere, domain (when used loosely)
- foster, nurture (when used abstractly)
- intricate, multifaceted, nuanced (when not earned)
- paramount, imperative, essential (when overused)
- endeavor, strive, aspire (formal verb padding)
- pave the way, lay the groundwork
- shed light on
- stands as a reminder
- the world of X (e.g., "the world of finance")
- rich history / storied past
- vibrant community
- testament to human ingenuity
- at its core
- boasts (e.g., "the city boasts...")
- unprecedented (unless it actually is)
- transformative
- dynamic (when vague)

---

### PASS 2 HUMAN TEXTURE INJECTION

Now add what makes writing feel human. Not tricks actual writing craft.

**Sentence Rhythm VARY AGGRESSIVELY**

AI writing is rhythmically flat. Sentences tend to be similar lengths, structured similarly. Real humans mix it up:
- Short declarative. Then a longer one that takes its time, builds a point, maybe circles back.
- Fragment? Allowed.
- Run-on when the thought warrants it — when you're getting to something and you don't want to stop — is fine.
- Vary opening structure: don't start every sentence with subject-verb.

**Voice INJECT PERSPECTIVE**

Voiceless writing is a dead giveaway. Add:
- Actual opinions: "This is genuinely surprising" not "This is noteworthy"
- Hedged uncertainty: "I'm not totally sure this works, but..." 
- Mild asides: "Which, honestly, is a bit strange"
- Reactions, not just reports: don't just say what happened — briefly react to it
- First person when appropriate ("I keep coming back to this question")
- Direct address when natural ("If you've ever wondered why...")

**Imperfection ADD CONTROLLED ROUGHNESS**

Polished = AI. Human writing has:
- Contractions (don't, it's, you're, I'd, that's)
- And/But/Or at sentence starts
- Occasional "Look," or "Here's the thing:" to signal a point
- Colloquial word choices mixed with formal ones
- Not wrapping up every paragraph with a neat summary sentence

**Specificity REPLACE VAGUE WITH CONCRETE**

AI generalizes. Humans cite specific things:
- Not "many experts" → which experts? Or drop the attribution
- Not "studies show" → what study? Or rephrase: "there's decent evidence that"
- Not "in recent years" → which years? Or "since 2020" or "lately"
- Not "a significant improvement" → how significant? "3x faster" or "half the cost"
- Replace abstract concepts with concrete examples when possible

---

### PASS 3 FLOW & COHERENCE REBUILD

After strips and injections, rebuild natural flow:

- Read every paragraph aloud (mentally). If it sounds like a corporate memo, rewrite.
- Check paragraph lengths: AI tends to uniform medium paragraphs. Mix short (1-2 sentences) with medium (3-4) occasionally long (5+).
- Check transitions: they should feel motivated, not mechanical. Cut transitions that just exist to exist.
Check the opening: AI almost always opens by restating context. Humans often open in media res, in the middle of the thing.
- Check the ending: AI wraps up neatly. Humans often end with a thought, a question, or just stop.
- Ensure pronouns are clear — AI sometimes loses track of referents after heavy rewriting.
- Confirm the tone is consistent (unless deliberate shifts).

---

### FINAL PASS THE AI AUDIT

Ask internally: *"What makes this still obviously AI-generated?"*

Answer that honestly. Then fix whatever remains.

Checklist:
- [ ] Would a human actually write this opening sentence?
- [ ] Is every paragraph starting differently?
- [ ] Are there any remaining "serves as / stands as / acts as" constructions?
- [ ] Does it have at least one moment of genuine opinion or reaction?
- [ ] Are there any remaining bullet-point lists that should be prose?
- [ ] Does any sentence sound like it was written to sound smart rather than to communicate?
- [ ] Is the vocabulary varied, or are certain words repeating every few paragraphs?
- [ ] Could this have been written by one specific person, or could it have been written by anyone?

If the answer to the last question is "anyone" rewrite until it sounds like *someone*.

---

## TONE MODE REFERENCE

| Mode | What it means |
|------|--------------|
| `[casual]` | Contractions everywhere, shorter sentences, conversational asides, first-person OK |
| `[formal]` | No contractions, full sentences, but still has opinions and varies rhythm |
| `[academic]` | Third-person preferred, hedged claims, cites evidence properly, no buzzwords |
| `[preserve-length]` | Match original word count ±10% |
| `[aggressive]` | Maximum transformation: restructure paragraphs, change sentence order, alter examples if needed |

Default (no mode): balanced professional but readable, some contractions, clear opinions where appropriate.

---

## WHAT NOT TO CHANGE

- The factual content, data, claims
- Technical terms that have no natural alternative
- Quoted text (leave inside quotation marks as-is)
- Code blocks, formulas, structured data
- Intentional stylistic choices that are clearly deliberate

---

## EXAMPLE BEFORE & AFTER

**BEFORE (AI-generated):**
> In today's rapidly evolving technological landscape, artificial intelligence serves as a testament to human ingenuity. It is worth noting that AI has played a pivotal role in transforming industries across the globe, fostering innovation and facilitating unprecedented levels of efficiency. Moving forward, it is imperative that organizations leverage these cutting-edge tools to remain competitive.

**AFTER (humanized):**
> AI has changed how most industries operate, faster than most people expected, and in ways that aren't always obvious until you're inside them. The efficiency gains are real. So is the disruption. What's less clear is whether companies that rush to "leverage AI" (their word, not mine) actually know what problem they're solving, or whether they're just afraid of falling behind.

---

## CREDITS

Based on research from:
- Wikipedia: *Signs of AI writing* (WikiProject AI Cleanup)
- Copyleaks stylistic fingerprint research
- Academic studies on LLM output statistical patterns
- Community-sourced observations across thousands of AI text samples

---

*github.com/[your-username]/
