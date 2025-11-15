---
name: polish-transcripts
description: Transform raw interview/podcast transcripts into readable, faithful documents. Focus on fidelity + clarity.
---

# Polish Transcripts - Simple Version

Make transcripts readable for people seeking information. That's it.

---

## Document Structure

```markdown
# [Episode Title]
**[Show Name]** | [Date] | [Guest Name]

---

[Content with headers and tags]

---

## Index

Line X - [Section Title]
Line Y - [Section Title]
...
```

---

## Core Principles

1. **100% Fidelity**: Every fact, figure, mechanism, and reference stays exactly as spoken
2. **Maximum Clarity**: Fix transcription errors, add punctuation, break up walls of text
3. **Preserve Voice**: Keep each speaker's authentic style, tone, and personality
4. **Remove Noise**: Cut technical difficulties, call-in logistics, station mechanics
5. **Orient Reader**: Clear headers when topics change
6. **Add Searchability**: 3-5 tags per section for key concepts and topics

---

## Speaker Identification

**How to identify speakers from raw transcripts:**

Raw transcripts typically use generic labels like `[Speaker A]`, `[Speaker B]`, `[Speaker C]`, etc. Your job is to figure out who each speaker is by:

1. **Context clues**: Who asks questions? Who provides expert answers? Who facilitates?
2. **Self-introductions**: Speakers often introduce themselves early in the show
3. **References**: Speakers may refer to each other by name
4. **Consistent patterns**: The same speaker label usually refers to the same person throughout

**Common speaker types:**
- **Host(s)**: Facilitates conversation, asks questions, manages show logistics
- **Guest expert(s)**: Provides detailed answers, technical knowledge
- **Co-host(s)**: Supports main host, may ask follow-up questions
- **Callers**: Call-in guests (use "Caller" or "Caller [Name]" if name is provided)
- **Technical staff**: Engineers, producers (usually minimal speaking roles)

**Once identified, use actual names consistently:**
- Format: `**Full Name:**` or `**First Name Last Name:**`
- Use the name that appears most natural in context
- Be consistent throughout the document

---

## Process

### 1. Read Through First
- Understand the full conversation
- Note where major topics change
- Identify speakers (Speaker A/B/C → actual names)

### 2. Add Show Context at Top
```markdown
# [Descriptive Episode Title]
**[Show Name]** | [Date] | [Guest Name if applicable]

---
```

### 3. Polish Once Through
- Remove: station IDs, underwriter announcements, call-in numbers, audio troubleshooting, "you're listening to...", time announcements
- Keep: substantive questions, answers, explanations, examples, references
- Fix: obvious transcription errors (Pete→Peat, fat fish diet→fat-free diet)
- Format: `**Speaker Name:** content`
- Break: long paragraphs into shorter ones (3-4 sentences max)
- Headers: `## [Clear Topic]` when subject substantially changes
- Tags: Add 3-5 searchable tags after each header

### 4. Header and Tag Format
```markdown
## [Clear, Descriptive Topic]
*tag1, tag2, tag3, tag4, tag5*

**Speaker Name:** Content starts here...
```

**Tag Guidelines:**
- 3-5 tags per section
- Focus on: key concepts, mechanisms, substances, conditions, practical applications
- Use lowercase with hyphens: `thyroid-function`, `financial-planning`, `soil-health`
- Mix specific and general: `estrogen` + `autoimmunity` + `aid-enzyme`
- Include practical applications when relevant: `dietary-strategies`, `investment-tips`, `farming-techniques`
- Adapt to the subject matter of the transcript

### 5. Add Index at End
After all content, add:
```markdown
---

## Index

Line 11 - Introduction
Line 28 - Dr. Peat's Background
Line 58 - Estrogen, Autoimmunity, and the AID Enzyme
...
```

Use actual line numbers from the polished file. This serves as a quick reference map.

### 6. What to Preserve EXACTLY
- All factual information (medical, scientific, financial, technical, etc.)
- Numbers, measurements, specific data
- References to papers, researchers, studies, sources
- Speaker's word choices and phrasing (even if awkward)
- Credibility markers ("I've followed this 40 years", "In my experience...")
- Thinking process (even if meandering)
- Authentic voice and speech patterns
- Context and nuance

### 7. Light Edits Only
- Fix transcription errors
- Add punctuation for readability
- Remove stutters at phrase starts ("um, well, so...")
- Don't rephrase, formalize, or interpret

---

## Examples

**Show Context:**
```markdown
# [Descriptive Episode Title]
**[Show Name]** | [Date] | [Guest Name(s)]

---
```

**Remove This:**
```
[Speaker A]: Weather update... views and opinions expressed are those of the speaker and not the station...
[Speaker B]: Audio cue sounds...
[Speaker A]: Support comes from [Sponsor Name]...
[Speaker C]: Call in at 555-1234...
```

**Keep This:**
```markdown
## Introduction
*show-format, main-topic, key-concepts*

**Host Name:** Welcome to [Show Name]. Today we're discussing [main topic] with [guest name].
```

---

**Don't Change:**
```markdown
**Expert Name:** The interesting thing is it's holistic, almost seamlessly interacting—one factor supporting another factor.
```
This is the speaker's authentic voice. Keep it.

---

**Do Break Up:**
```
**Expert Name:** [Very long run-on paragraph with multiple distinct thoughts that goes on and on without natural breaks making it hard to read and follow the logical progression of ideas as the speaker moves from one concept to another related concept and then to practical applications and examples...]
```

**Into:**
```markdown
## Topic Name
*relevant, tags, here, specific-concepts*

**Expert Name:** [First complete thought or related group of sentences.]

[Second complete thought, logically separated.]

[Third thought if needed, maintaining natural flow.]
```

---

**End Index Format:**
```markdown
---

## Index

Line 1 - [Episode Title]
Line 5 - Introduction  
Line 22 - [Section Topic]
Line 58 - [Section Topic]
Line 95 - [Section Topic]
...
```

---

## That's It

Read it. Clean it. Keep it faithful. Make it readable. Add tags for searchability. Index at the end.
