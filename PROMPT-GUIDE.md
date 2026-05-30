# PROMPT GUIDE — The Content Repurposing Machine

**How to use all 5 prompts as one connected workflow**

---

## Overview

This guide turns the five prompt files into a sequential 90-minute session. Each prompt builds on the previous one. By the end, you have taken a single piece of source content and produced:

1. 10 different opening hooks
2. A platform-optimized social media caption
3. A 10-slide carousel outline
4. A short-form video script
5. A newsletter issue

All from the same original idea. All ready to schedule or publish.

---

## Before You Start: Prepare Your Source Content

The quality of your output depends entirely on the quality of your source material. Good source content has at least one of these qualities:

- **A clear process or system** ("How I plan my week in 30 minutes")
- **A specific result** ("How I got my first 500 email subscribers")
- **A counterintuitive opinion** ("Consistency is overrated — here's what actually works")
- **A story with a lesson** ("A client ghosted me after 6 months — here's what I learned")
- **A common mistake and fix** ("The pricing mistake most freelancers make in their first year")

Vague topics produce generic output. The more specific your source, the better every prompt will perform.

**Prepare your source content as a paragraph or bullet list.** You will paste this into each prompt. Something like:

> "I used to create content from scratch every day. Then I started keeping a 'content core' — one detailed thread or article per week that I wrote carefully. From that, I pulled 5 tweets, 1 carousel, 1 video script, and 1 newsletter section. It cut my daily content time from 2 hours to 30 minutes and my output actually increased."

That's all you need. A specific, real insight told plainly.

---

## Step 1: hook-prompt.txt — Generate Your Hooks First

**File:** `prompts/hook-prompt.txt`

**Why this goes first:** Your hook is the most important sentence in any piece of content. It determines whether anyone reads the caption, watches the video, or clicks the carousel. Starting with 10 hook options means every piece of content that follows starts from the strongest possible opening.

**How to use it:**

1. Open `hook-prompt.txt`
2. Replace `[INSERT YOUR MAIN TOPIC OR NUGGET]` with a single sentence describing your source content. Example: *"How I cut my daily content creation time from 2 hours to 30 minutes by writing one core piece per week"*
3. Paste into your AI tool
4. Review all 10 hooks it generates

**What to do with the output:** Read all 10 hooks. Star or copy the 2–3 that feel most natural to your voice and most relevant to your audience. These become your opening lines in every subsequent prompt.

**Tips:**
- The "Bold Statement" and "Pattern Interrupt" hook types consistently generate the highest engagement for educational content. Prioritize those when picking your top hooks.
- Don't use the hook verbatim if it sounds robotic. Edit it to sound like how you actually talk.
- If all 10 feel off, your topic description was too vague. Rewrite the topic sentence with a specific number, result, or concrete detail, and run the prompt again.

**Common mistake:** Picking the "safest" hook instead of the most compelling one. Hooks that feel slightly uncomfortable to post often perform best. If a hook makes you think "is this too much?" — test it.

---

## Step 2: caption-prompt.txt — Write Your Main Caption

**File:** `prompts/caption-prompt.txt`

**Why this is second:** You have your best hook from Step 1. Now you build the full caption around it. The caption is the centerpiece piece — the one that goes on your primary platform (usually Instagram or LinkedIn) and ties everything together.

**How to use it:**

1. Open `caption-prompt.txt`
2. Fill in all the bracketed fields:
   - `[PLATFORM]` — pick one (Instagram, LinkedIn, TikTok, or Twitter/X)
   - `[CUT AND PASTE YOUR NUGGET]` — paste your full source content paragraph
   - `[DESCRIBE YOUR AUDIENCE]` — be specific ("solo freelancers 1–3 years in who want more stable income")
   - `[Professional/Educational/Entertaining/Conversational]` — pick one tone
   - `[SHORT/MEDIUM/LONG]` — pick one length based on your platform
   - `[PREFERRED STYLE]` — describe your voice ("conversational, like explaining to a friend over coffee, no jargon")
3. Open the caption with the best hook from Step 1. Paste the hook into the SOURCE CONTENT field before the rest of your content
4. Paste the completed prompt into your AI tool

**What to do with the output:** The AI will generate the caption, CTA, and hashtags as separate sections. Edit the caption for your voice — look especially at the first line (your hook) and the CTA. Both should sound like you.

**Tips:**
- Run this prompt twice with two different hooks from Step 1. Compare both outputs and take the stronger one.
- For Instagram: the first 125 characters (before "more") must hook the reader. Count your first sentence — if it's longer than 125 characters, trim it.
- For LinkedIn: end the caption with a direct question. LinkedIn's algorithm rewards comments, and a question is the fastest way to generate them.
- Delete any hashtags the AI generates that don't feel relevant. 5 precise hashtags outperform 30 generic ones.

**Common mistake:** Keeping the AI's call to action without rewriting it. Generic CTAs like "let me know in the comments!" convert poorly. Replace with specific CTAs: "What's the one piece of content you create that takes the longest? Drop it below."

---

## Step 3: carousel-prompt.txt — Build the Carousel Outline

**File:** `prompts/carousel-prompt.txt`

**Why this is third:** Carousels require the most structure of any content format. They have a specific slide-by-slide architecture that the AI handles well once it understands your topic. Building the carousel after the caption means you've already clarified your core message — the carousel expands it into a multi-slide educational format.

**How to use it:**

1. Open `carousel-prompt.txt`
2. Replace `[INSERT YOUR MAIN TOPIC]` with the same topic description you used in Step 1
3. Add one line to the prompt (after the topic): "Opening hook for Slide 1: [paste your best hook from Step 1]"
4. Paste the completed prompt into your AI tool

**What to do with the output:** The AI will generate slide-by-slide headlines. For each content slide (slides 4–8), you'll need to add 2–3 lines of body text and a visual concept. The prompt gives you the skeleton — you add the flesh.

**The carousel structure to follow:**
- Slide 1: Hook (the output from Step 1 — use one of your top hooks)
- Slide 2: Tease (what they'll learn by the end)
- Slide 3: Setup (the problem or context)
- Slides 4–8: One point per slide, one visual per slide
- Slide 9: CTA (specific and direct — not "follow me")
- Slide 10: Your bio + a secondary CTA (link in bio, download, etc.)

**Tips:**
- Each slide should be readable in under 5 seconds. If there's more than one idea on a slide, split it.
- Use your caption (from Step 2) as the caption for the carousel post. They're synergistic — the caption hooks the viewer, the carousel delivers the detail.
- For Canva: build Slide 1 first. If it doesn't stop the scroll in isolation, redesign it before building the rest.

**Common mistake:** Overloading slides 4–8 with text. Real carousel slides have a short headline and 1–2 bullet points maximum. The AI will sometimes generate too much text for a single slide — break those slides into two.

---

## Step 4: video-script-prompt.txt — Write the Video Script

**File:** `prompts/video-script-prompt.txt`

**Why this is fourth:** By this point you've refined your message through a caption and a carousel. Your core points are clear. The video script is the spoken version of the same message — shorter, punchier, and structured for someone watching, not reading.

**How to use it:**

1. Open `video-script-prompt.txt`
2. Replace `[30/60/90]` with your target video length. For most short-form platforms: 30 seconds for TikTok/Reels, 60 seconds for a slightly deeper take, 90 seconds maximum.
3. Replace `[INSERT YOUR TOPIC]` with your topic
4. Add: "Opening hook: [paste your best hook from Step 1]"
5. Add: "Key points to cover: [paste the main points from your carousel slides 4–8]"
6. Paste the completed prompt into your AI tool

**What to do with the output:** The script is a starting point, not a teleprompter. Read it aloud before recording. Every sentence that sounds stiff or unnatural — rewrite it. Your video should sound like how you talk, not like how you write.

**The video structure:**
- Hook (0–3 sec): The stop-scroll opener. Use the exact hook from Step 1.
- Context (3–10 sec): Why this matters and who it's for.
- Main point(s) (10–50 sec): The actual content. For 30-second videos, one main point only. For 60–90 seconds, two or three points maximum.
- CTA (last 5 sec): One specific action. "Follow for more" is weak. "Comment [keyword] and I'll send you the template" is specific and drives algorithm signals.

**Tips:**
- Record 3–5 takes. The first is always the stiffest. The third or fourth take usually sounds the most natural.
- Don't script the hook word-for-word. Instead, internalize what you want to say and deliver it naturally with energy. Read everything else from the script.
- Captions/subtitles are non-optional. 85% of social video is watched without sound. Use CapCut, Descript, or your platform's built-in auto-caption tool.

**Common mistake:** Writing a script and then reading it stiffly to camera. If you're not comfortable on camera yet, record yourself explaining the topic conversationally first, transcribe that recording, and use that transcription as your actual script. It will sound 10x more natural.

---

## Step 5: newsletter-prompt.txt — Convert to a Newsletter

**File:** `prompts/newsletter-prompt.txt`

**Why this is last:** The newsletter is the longest format. Writing it last ensures you're not retreading ground you've already covered in the other formats — you're synthesizing and adding depth. Newsletter readers expect more than a caption or a carousel. They gave you their email address. Give them the full picture.

**How to use it:**

1. Open `newsletter-prompt.txt`
2. Replace `[TOPIC]` with your topic
3. Replace `[AUDIENCE]` with your specific audience description
4. Add: "Source content: [paste your full source content paragraph]"
5. Add: "Key points already covered in social content: [list the main points from your carousel]"
6. Add: "For the newsletter, go deeper on [specific aspect you couldn't cover in short-form content]"
7. Paste into your AI tool

**What to do with the output:** The AI will generate a full newsletter structure including subject lines, preview text, hook paragraph, main content, key takeaway, CTA, and P.S. Edit each section for your voice. The subject lines especially — the AI tends to generate safe subject lines. Test your own more specific version against its suggestion.

**The newsletter structure:**
- Subject line (3 options): one question, one stat/number, one curiosity-gap
- Preview text: the sentence that appears in the inbox after the subject line
- Greeting: personal opener
- Hook paragraph: why you're writing this today and why it matters to the reader
- Main content: the fuller version of your source insight — with more examples and depth than any social format
- Key takeaway: one sentence that summarizes the point
- CTA: what you want them to do (reply, click, share, buy)
- P.S.: secondary ask or link

**Tips:**
- The best newsletter subject lines include a specific number, a name, or a concrete result. Compare: "How to create better content" vs. "I cut my content time by 75%. Here's the system." The second one gets opened.
- End with a genuine question in your CTA. "Hit reply and tell me your biggest content bottleneck" generates real replies, which improve deliverability and give you material for future content.
- The newsletter and the carousel should feel complementary, not redundant. The carousel is the "what" — the newsletter is the "why" and "how much deeper can we go."

**Common mistake:** Publishing the AI's newsletter output without personalizing the greeting and hook. These are the sections readers use to decide whether the email feels human or automated. A generic "Hey there, hope you're having a great week!" opener is worse than no opener. Make it specific to what's happening in your world or your audience's world right now.

---

## The Full 90-Minute Session Plan

| Time | Activity |
|------|----------|
| 0:00–0:10 | Prepare source content (write or find your core insight) |
| 0:10–0:20 | Run hook-prompt.txt. Pick top 2–3 hooks. |
| 0:20–0:35 | Run caption-prompt.txt. Edit for voice. Caption done. |
| 0:35–0:50 | Run carousel-prompt.txt. Fill in slide body text. Carousel outline done. |
| 0:50–1:05 | Run video-script-prompt.txt. Read aloud. Edit. Script done. |
| 1:05–1:30 | Run newsletter-prompt.txt. Personalize greeting and hook. Newsletter done. |

After the session: schedule the caption (and carousel when designed), record the video, queue the newsletter.

---

## Common Mistakes Summary

- **Vague source content:** "Tips for entrepreneurs" will produce generic output. "How I got my first retainer client without a portfolio" will produce specific, useful content. Be specific.
- **No hook at the start of every piece:** Every format — caption, video, carousel slide 1, newsletter subject line — lives or dies by its opening. Use the hooks from Step 1 everywhere.
- **Publishing AI output without editing:** The prompts produce strong drafts. Your job is to make them sound like you. Budget at least 10 minutes per piece for editing.
- **Skipping the CTA:** Every piece of content needs one specific action. "Follow for more" is not a CTA. "Download the free template — link in bio" is.
- **Trying to use all five prompts for different topics:** The power of this system is coherence. One idea, five formats, one 90-minute session. Stick to one topic per session.
