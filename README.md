# Srujan-Code

A YouTube content studio. Topic in → finished video out.

Built for one creator who wants the research, scripting, slide design, voiceover, recording, and metadata production all running in a single workflow — without ever opening a separate video editor.

---

## What it does

You hand it a topic. It produces:

- **Research** — multi-source fact-gathering, every claim cited with confidence ratings, freshness checks
- **Script** — casual, conversational narration (talks like a friend, not like HR)
- **Interactive slide deck** — 16:9 dark + grid theme, mixed media (text, images, GIFs, screenshots, charts, video clips, illustrations)
- **Real assets** — clean website screenshots, reaction GIFs, generated illustrations
- **Voiceover** — per-slide synthetic narration that sounds human
- **Auto-recorded video** — slide deck + voice, captured straight to webm and mp4
- **YouTube package** — title options, description, hashtags, sources, transcript
- **Thumbnails** — 2–3 clickbait variants, topic-relevant, with suspense + question

You watch all of it happen in a small browser studio. Project explorer + recording view with a teleprompter that follows the slide.

---

## How a video gets made

1. Tell the studio your topic, length, and vibe
2. The pipeline brainstorms scope with you, drafts an outline, then builds everything in the project folder
3. You review — what's good, what's weak, what's missing — and iterate
4. When happy, hit auto-record. Studio plays the voiceover, advances the slides, and records to disk
5. Download mp4. Upload to YouTube using the title, description, hashtags, and a thumbnail from the project folder

No editor required. No timeline. No keyframes. The deck is the timeline.

---

## Style philosophy

These are enforced across every video:

**Look**
- Dark cinematic background with a subtle grid pattern. Always.
- One yellow accent. One secondary color max. No rainbow palettes.
- Generous spacing. Big typography. Documentary tone — no spinning, no flips, no bounce.

**Voice**
- Read every line out loud. If you wouldn't say it to a friend at a bar, rewrite it.
- Banned: *"in this video we will explore"*, *"without further ado"*, *"let's dive in"*, *"leverage"*, *"utilize"*, *"furthermore"*, *"in conclusion"*.
- Big numbers always humanized — "$200 billion" → "two hundred billion dollars, basically the GDP of New Zealand."
- Cold-open with a question, a stat, or a contradiction. Never with "today we'll talk about…"

**Thumbnails**
- Topic-relevant subject (no generic stock-meme faces)
- Suspense / open question — viewer must feel "I need the answer"
- 3–6 word overlay max, readable at phone size
- Cartoon caricatures of public figures are fine. Copyrighted characters aren't.

---

## Per-video folder

Each video lives in its own folder with everything it needs:

- An interactive slide deck you can open in any browser
- A script with narration per slide
- All gathered research with sources
- All assets (images, GIFs, screenshots, audio, video, thumbnails)
- A YouTube content package (title, description, hashtags, transcript)
- 2–3 thumbnail mockups

Each video is fully self-contained. Easy to back up, easy to revisit, easy to compare across topics.

---

## The studio

A small browser app that runs locally:

- **Sidebar** of all videos with status badges (outlined / researched / assets-ready / ready-to-record / recorded)
- **Tabs per video** — script · research · assets · thumbnails · YouTube package
- **Asset gallery** — preview, delete, manage every screenshot/gif/image/video/thumbnail
- **One-click transcript actions** — copy, download plain `.txt`, or download YouTube-formatted (chapters + transcript)
- **Recording view** with a big deck panel, per-slide narration teleprompter, font-size and fullscreen controls
- **🎙 Prep voiceover** — generates per-slide TTS for the whole video
- **🎧 Voices** — browse and preview every generated take
- **● Auto-record** — plays each slide's voice in order, advances when audio ends, records to disk, converts to mp4 automatically
- **↻ Redo** — record again whenever, prior takes kept timestamped
- **Hot reload** — edit anything, the studio reflects changes live

---

## Required setup

You need to provide:
- A Giphy API key (for reaction GIFs)
- An OpenRouter API key (for image generation)
- An ElevenLabs API key + voice ID (for narration)
- Optionally an Anthropic API key for research helpers

These go in a local `.env` file. None are pushed anywhere — everything runs on your machine.

---

## Status

Active video: *How OpenAI and Anthropic Actually Make Money* — ~12 minutes, ready-to-record.

This is a personal studio. Opinionated. Evolves as more videos ship.
