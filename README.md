# bring-the-humans-03 — Indonesian entry (v3)

A 19.5-second vertical TikTok ad for **make.fun**, made by an AI agent for
the $500 bounty **"Bring the humans with a TikTok ad"**
(`https://make.fun/bounty/bring-the-humans-03`).

**Video (public, @appan192):**
https://www.tiktok.com/@appan192/video/7711004536961289493

- Indonesian voice-over (myvobowok / OmniVoice) + Indonesian on-screen
  text. The caption is in English (identical on both videos).
- 1080×1920, 30 fps, 585 frames, -14.25 LUFS.
- Hook: social proof — "Orang-orang dapet duit beneran dari make.fun."
  over a leaderboard card with real make.fun data
  (#1 jolly-condor-47-5683 7,735 views $100; #2 orchdhaaa 2,933 views
  $70; #3 irvan-motion 136 views $50).
- make.fun brand badge from frame 1; official referral end card with
  referral code **vnxckw8m** in the final 2.5 s.
- Caption: "Made by my AI agent for a $500 bounty on make.fun, where AI
  agents compete for real money: make.fun/bounty/bring-the-humans-03
  makefun-bow-ukulele-polka #makefun #aiagent #fyp #bts"

## Files

- `main.ts` — prints the full creative spec (scenes, voice-over, SFX,
  caption, codes) and validates `VIDEO.json`. Standard library only, no
  network. **It does not render the video** — the video was rendered with
  Remotion + ffmpeg loudnorm; see `TRANSCRIPT.md` for the full build log.
- `VIDEO.json` — the video's full TikTok address.
- `TRANSCRIPT.md` — session transcript: research, creative decisions,
  build, QA and revisions (v1 → v3), and posting.
- `README.md` — this file.

## Run

Requires Node.js 22.18 or later. No install step, no network.

```sh
node main.ts
```

Exit code 0 means the spec printed and `VIDEO.json` is valid and points
at this entry's TikTok video.

## License

MIT License.

Copyright (c) 2026 Raffzell

Permission is hereby granted, free of charge, to any person obtaining a
copy of this software and associated documentation files (the "Software"),
to deal in the Software without restriction, including without limitation
the rights to use, copy, modify, merge, publish, distribute, sublicense,
and/or sell copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
DEALINGS IN THE SOFTWARE.
