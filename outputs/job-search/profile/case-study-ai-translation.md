# Case Study: From 208 Specialists to 10 — AI Translation at Scale

**Role:** Senior Product Owner, Refinitiv Eikon (LSEG)
**Period:** Dec 2019 to Jul 2021
**Format:** 5-slide deck (this doc is the source content; build the visual in Google Slides / Keynote / PowerPoint)

---

## How to use this doc

Each section below is one slide. Headers are slide titles, bullet content goes on the slide, the prose under each section is the speaker note / context for you when presenting or writing the LinkedIn caption.

When the deck is built, export to PDF and pin to your LinkedIn Featured section.

---

## Slide 1: The 30-Second Story

**60+ language pairs. 208 specialists doing manual translation. Slow, expensive, hard to scale.**

We built an AI translation pipeline that maintained 90%+ accuracy across the language portfolio while scaling the team from 208 to 10.

**The numbers:**
- 208 to 10 specialists (20x scale on team capacity)
- 90%+ minimum accuracy across 60+ language pairs
- 50% improvement in cycle times
- 30% productivity increase on adjacent content workflows
- 45% reduction in translation-related customer cases

*Speaker note: This is the hook slide. Lead with the headline number (208 to 10) and the quality bar (90%+) in the same breath, so it doesn't read as a quality vs cost trade-off.*

---

## Slide 2: The Problem

Refinitiv Eikon delivered financial markets data and content to traders and investors across the globe. Content had to be translated, classified, and curated in 60+ languages.

The manual approach didn't scale:
- 208 language specialists translating by hand
- High cost per translation
- Slow turnaround on time-sensitive market events
- Quality varied by language and by individual
- Hiring and training new specialists took quarters

**The bet:** could AI carry the volume while keeping a quality bar that financial professionals could trust?

*Speaker note: The audience for this content is financial professionals making real decisions on real money. That framing matters because it explains why we couldn't just ship a generic AI translation API.*

---

## Slide 3: The Approach

**Hypothesis:** AI-led translation with humans in the loop for QA and edge cases could scale capacity 10x to 20x without sacrificing accuracy.

**Four key decisions:**

**1. Build, not buy.** General-purpose translation APIs missed financial terminology and context. We built on top of Refinitiv Data Platform (AWS) to integrate with the existing content ingestion pipeline.

**2. Define the quality bar upfront, in numbers.** 90% minimum average accuracy per language pair, measured weekly against a holdout set. Below that bar, the language stayed human-led until the model caught up.

**3. Redeploy, don't replace.** The 10 specialists who stayed weren't junior survivors. They became the senior QA layer: edge case adjudicators, training data curators, and language-pair owners.

**4. Phase the rollout.** High-volume / lower-stakes languages first. High-stakes / low-volume held back until accuracy matured.

*Speaker note: The "redeploy, don't replace" decision is the one most people miss. The technology was the easy part. The org design around it was the work.*

---

## Slide 4: What We Shipped

**The AI translation pipeline:**
- Automated content ingestion from 35+ global markets
- AI-led translation across 60+ language pairs
- Human-in-the-loop QA with sampling and edge case escalation
- Integration with Refinitiv Data Platform serving 1,000+ end-users
- Open APIs for B2B and B2C content delivery

**Adjacent ML/NLP capabilities** (same platform foundation):
- 250+ structured and unstructured attributes extracted from raw market feeds
- Workflow automation for content curation and refinement

**Outcomes:**
- 208 to 10 translator team
- 90%+ accuracy maintained across the language portfolio
- 50% improvement in cycle times
- 45% reduction in translation-related customer cases
- 30% productivity improvement on adjacent content workflows
- 25% increase in content enhancement throughput

*Speaker note: The "adjacent ML/NLP capabilities" matter because they prove the platform investment paid off beyond translation. One foundation, multiple wins.*

---

## Slide 5: What I Learned

**1. AI is best at removing toil, not judgment.** The 10 specialists who stayed weren't watching the AI work. They were the judgment layer: model training, edge case adjudication, quality drift detection. The AI did the volume; humans owned the bar.

**2. Quality bars must be explicit and measurable, set upfront.** "Maintain quality" doesn't survive contact with an AI rollout. "90%+ minimum average accuracy per language pair, measured weekly against a holdout set" does.

**3. Change management matters more than the technology.** Building the AI was 20% of the work. Redesigning roles, redeploying domain experts, communicating the change, and earning trust internally was 80%. Get this wrong and the technology doesn't matter.

**4. Don't measure AI accuracy. Measure combined human + AI output quality.** The pipeline's job was to deliver trusted financial content, not pass an AI benchmark. The right metric is what reaches the customer, not what the model scores in isolation.

**5. What I'd do differently.** Get the redeployment plan signed off BEFORE announcing the AI rollout. We did it in parallel and it created unnecessary anxiety in the team. The technology was reversible; trust was harder to rebuild.

*Speaker note: Lesson 5 is the one hiring managers will respect most. Honest reflection on what went wrong signals seniority more than any results chart.*

---

## Caption / LinkedIn post when you publish this

When you pin the PDF to Featured, write a short caption above it. Suggested:

```
Pinned a case study on the AI translation work I led at Refinitiv (LSEG): 208 specialists down to 10 across 60+ language pairs, with 90%+ accuracy maintained.

The technology was 20% of the work. The other 80% was redesigning roles, redeploying domain experts, and earning trust internally before the rollout.

Five lessons inside, including the one I'd do differently next time.

#ProductManagement #AI #DataProducts
```

---

## Anonymization notes

This case study is built on facts from your Refinitiv resume entry, all of which are public on your LinkedIn. No internal codenames, customer names, or proprietary architecture details are referenced.

If your former team or LSEG legal would object to any specific number being public (e.g., the 208 figure), swap for ranges:
- "208 to 10" → "a senior specialist team in the low-200s, scaled down to ~10"
- "1,000+ end-users" → "a multi-thousand end-user base"
- "60+ language pairs" → "across the full enterprise language portfolio"

The story works either way; specific numbers add credibility but ranges still make the point.

---

## Next steps

1. Build the visual deck (5 slides + optional title slide). Recommend Google Slides or Keynote with a clean, minimal template; one bold number per slide where applicable.
2. Export to PDF.
3. Upload to LinkedIn Featured section with the caption above.
4. Optional: convert the same content to a LinkedIn article post for reach. Same story, longer prose form.
