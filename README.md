# Viral-Social-Media-Content-Automation-Pipeline

Just import the JSON file to your N8N flow, and proceed to enter all the API keys and other keys, link your accounts, add instances of your credentials, etc and you're done.

Stage 1 — Discovery: Five live data feeds (Google Trends, Reddit, X, YouTube Trending, TikTok Creative Center) all funnel into a GPT-4o Viral Score Engine that ranks topics on a shock × monetisability matrix and picks the day's winner.
Stage 2 — AI Generation: GPT-4o writes the script (hook under 3 seconds, 3 body beats, CTA). HeyGen generates the avatar video, Runway ML produces cinematic B-roll, ElevenLabs handles voiceover, and Epidemic Sound auto-selects royalty-free music. FFmpeg assembles the final 9:16 and 16:9 files.
Stage 3 — Platform Packaging: GPT-4o writes completely different metadata for each platform — Facebook gets 2200-char descriptions with 5 hashtags, YouTube gets SEO-engineered titles + 5000-char keyword-rich descriptions + 15 tags, Instagram gets a first-line hook caption + 30 hashtags + alt-text.
Stage 4 — Scheduling: n8n Cron posts within empirically proven peak windows (FB 12–3pm, YT 2–4pm & 8–11pm, IG 6–9am & 6–9pm IST) and dynamically shifts those windows weekly based on your own PostgreSQL engagement data.
Stage 5 — Publishing: Native API calls — Facebook Graph API v20, YouTube Data API v3, Instagram Content Publishing API — with confirmation logged to PostgreSQL and a Slack alert on every publish or failure.
Stage 6 — Engagement: Polls every 30 min for 48 hours, GPT-4o auto-replies to questions and high-like comments within 2 hours, a sentiment classifier routes toxic comments to hide+report, and a demand-signal extractor feeds recurring audience requests back into next day's topic picker.
Stage 7 — Monetisation: Tracks YPP eligibility, AdSense RPM, brand deal fit detection, affiliate UTM tracking, and Gumroad digital product CTAs — all in a weekly Slack revenue digest.
Stage 8 — Feedback Loop: Every Sunday, a GPT-4o strategy session reads your last 7 days of data and rewrites topic weights, hook formulas, and peak-hour windows. You get a Slack approve/override button before it commits.
Total tool stack cost: ~$341/month. The biggest lever — if budget is tight, swap Runway ML for Pexels stock footage first (saves ~$95/month with minimal quality loss on most topics).
