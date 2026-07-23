# fam-fatale — Story Repo Harness

## What this repo actually is

This is not a clean bible. It's raw ore — voice-note-style, stream-of-consciousness brainstorm sessions, transcribed and dumped. 10die thinks out loud, mid-sentence, associatively. That means:

- Contradictions aren't mistakes. They're the idea evolving in real time.
- Names get overwritten inline ("wait, no — check that...").
- The best material is buried inside run-on paragraphs, not offered up clean.
- A later session usually supersedes an earlier one — but not always. Don't assume.

The job of anyone (human or AI) working in this repo is **extraction, not invention.** Mine the nuggets out. Never paper over a gap by making something up to fill it.

## Folder structure

/raw — verbatim source material, dated. NEVER edited, cleaned, or corrected.

/canon/OPEN_QUESTIONS.md — unresolved contradictions and undecided names. Living doc.

/canon

/forces

/mechanics

/characters

/arcs

/engine

## Rules

1. **Raw stays raw.** Chat exports, voice transcripts, this file's source material — all of it lives in `/raw` untouched, forever. If you need a fact from it, copy the fact INTO a canon file with a `source:` citation pointing back to the raw file and date. Never rewrite the raw file itself. It's the record you can always re-check against when memory of "what did I actually say" gets fuzzy.

2. **Every canon entry cites its source.** `source: raw/2026-07-09-chat.md, para 4`. If a contradiction shows up later, this is how you find out which version is older without re-reading everything.

3. **Contradictions go in OPEN_QUESTIONS.md, not into canon by guess.** When mining turns up two versions of a fact, log both, note which session came later, and leave it unresolved until 10die says which one wins. Do not silently pick the "more coherent" one — coherence isn't the same as correct.

4. **Don't clean up the voice when quoting source material for reference.** Paraphrase is fine for canon summaries. But if you're pointing back at a raw passage to explain why a decision was made, preserve the rawness — it carries tone and priority that a tidy paraphrase loses.

5. **When drafting scenes, match established texture, not generic prose.** Damage is "banged," not "defeated." MODs are personal and physically logical extensions of effort, not arbitrary powers. Fights are legible — a reader should be able to track who's winning and why without narration doing the work.

## Mining protocol (for processing new raw dumps)

1. Read the full raw entry once, straight through, no note-taking.
2. Second pass: tag each nugget by type — `character`, `mechanic`, `plot`, `theme`, `worldbuilding`, `contradiction`.
3. Write each tagged nugget into its matching canon file, cited.
4. Anything that conflicts with existing canon → OPEN_QUESTIONS.md, both versions logged, not resolved.
5. Don't summarize the raw file elsewhere and call it done — the canon files are the only thing anyone should need to read to work on this story going forward. Raw is backup, not reference material for daily use.
