# Listening for Medical Terms — A Plain-Language Guide

A single-page, self-contained HTML explainer that makes a technical pipeline —
**medical-term retrieval with audio embeddings** — understandable to non-technical readers.

**Think of it like Shazam, but instead of naming a song, it names the medical term it just heard.**

## What's inside

Open `index.html` in any browser. No build step, no dependencies.

The page covers, in plain language:

- **The problem** — speech-to-text mishears medical words ("metformin" → "met for men"),
  and the original *sound* is a second source of evidence when the transcript is wrong.
- **The big idea** — a curated medical dictionary + reference pronunciations + comparing
  sounds as numbers (audio embeddings).
- **The six-phase workflow** — from building the versioned terminology corpus, through
  reference pronunciation generation and vector indexing, to search, evidence fusion,
  and honest evaluation. Each phase is badged as built / partial / planned.
- **An interactive demo** — three clickable scenarios (clear voice, noisy room, unrelated
  chatter) showing how a recording becomes a ranked candidate list, and why a high
  similarity score is a *hint, not a proof*.
- **Built vs. planned** — an honest scoreboard of what the underlying system does today
  versus what is still roadmap work.
- **Safety principles** — a human always decides, "I don't know" is a valid answer,
  every answer is auditable, and no clinical claims are made.
- **Jargon buster** — embedding, cosine similarity, RAG, ASR, TTS, LASA, and more,
  each translated into one sentence.

## Scope

This page is a plain-language rendering of the technical document
*"Medical-Term Retrieval with Audio Embeddings."* It describes a reviewer-assistance
research prototype. It is **not** medical software, provides no medical advice, and makes
no diagnostic, prescribing, or medication-safety claims. Scores shown in the demo are
illustrative.
