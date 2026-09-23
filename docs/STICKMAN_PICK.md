# Stickman Weekly Loop: optional PICK handoff

This is an optional use of YouTube Pro for the beginning of the existing
**Pick → Write → Voice → Picture → Build → Ship → Learn** guide. It does not
change the approved production loop. Use the current `Stickman_Weekly_Loop.md`
and `CHANNEL_CARD.md` as the authority if they change.

## One episode, 35 minutes

1. Open Research. Stickman PICK is on by default in this adaptation. You can
   switch back to the general YouTube Pro workflow with **Use general workflow**.
2. Spend up to ten minutes finding a relevant public audience question in
   English or Spanish. Record its direct URL and paraphrase it without names.
   Do not infer an author's age from a profile image.
3. Run **one narrow YouTube search** about that situation. Inspect the actual
   sample, coverage warnings, and the proposed ideas. Public video metadata
   helps with packaging; it cannot prove audience demand, identify viewer
   demographics, or support a clinical claim.
4. Select one *candidate* idea. Enter your audience question and its HTTPS
   source URL in the PICK handoff, optionally add an everyday story situation,
   and download draft `01_brief.md`. If an idea is a poor fit, change it or
   return to the guide's manual PICK prompt; do not force the idea.
5. In the existing guide, check up to three factual claims against direct
   primary sources (date, population, precise support and limits), verify one
   Bible passage and named translation, and adjust the story and promise. The
   exported slots deliberately say UNKNOWN. An AI label is not verification.
6. Only after your own review, save the *completed* `01_brief.md` into the
   episode folder, mark PICK APPROVED in `RUN_CARD`, and continue with the
   existing WRITE prompt for a 4–5 minute Spanish story. Voice, Flow pictures,
   CapCut build, human upload, and the seven-day Studio review stay in that
   guide. If research exceeds 35 minutes, use an already checked question.

The question and optional story seed are kept in the current browser's local
workflow history. A new search produces a new snapshot and clears the handoff
fields shown for the old one. Downloaded files are yours to save in the episode
folder. The export never marks human approval, invokes Script Writer, or
publishes.

## Runtime and costs

- Run this app locally using the repository's Node.js 22.12+ setup and your
  YouTube Data API key. Gemini text ideas require a separate Gemini API key.
  Actual account compatibility and a complete run on the user's Android 8
  device have not been validated.
- This handoff adds **zero provider requests**. Research and AI Insights/Ideas
  have their existing provider calls. YouTube's current quota should be
  checked in Google Cloud before use. Avoid repeated searches merely to
  vary a title.
- Do not open Thumbnail Creator for a strict $0 API workflow. The repo's
  default Gemini image generation is not on Google's free API tier. Follow
  the existing CapCut thumbnail step using the locked character.
- API keys stay on the local server. Do not expose the app to the internet;
  its Settings endpoint assumes direct loopback access. Browser history does
  not sync between the phone and a PC.

This mode is an evidence-aware **PICK draft**, not medical research,
an automatic scripture checker, a Spanish script writer, or a channel
analytics integration.
