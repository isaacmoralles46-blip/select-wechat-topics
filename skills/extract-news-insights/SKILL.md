---
name: extract-news-insights
description: "Extract non-obvious, defensible cognitive insights from a news story and turn them into strong opinion angles for ordinary readers. Use when the user provides a news article, link, event, announcement, policy, product release, controversy, or public discussion and asks for 隐藏观点, 认知观点, 深层逻辑, 反常识角度, 新闻解读, 公众号观点, or an angle most readers may have overlooked."
---

# Extract News Insights

Find the important idea underneath a news story without forcing contrarianism. Build every viewpoint on verified facts, a clear mechanism, and a practical implication for ordinary readers.

## Establish the factual base

1. Read the supplied article, link, excerpt, or event description in full.
2. For current or externally verifiable news, browse the web and check the original announcement or primary source plus reliable independent reporting when available.
3. Record the event date separately from the article publication date.
4. Separate four layers before interpreting:
   - Confirmed facts.
   - Claims made by interested parties.
   - Unresolved or disputed points.
   - The article's framing and emotional language.
5. Do not build a viewpoint on a detail that remains unverified. Mark uncertainty plainly.

If the supplied material is too thin to support a meaningful view, research further or ask for the full source instead of padding the answer.

## Search beneath the headline

Ask what actually changed in the distribution of money, power, time, risk, access, trust, status, or responsibility.

Read [references/insight-lenses.md](references/insight-lenses.md) and apply only the lenses that fit the story. Generate several candidate interpretations before choosing one. Do not treat every lens as a box that must be filled.

For each candidate, write the logic as a causal chain:

`verified change → incentive or constraint → behavior change → second-order effect → ordinary person's implication`

Reject a chain when any arrow depends mainly on speculation.

## Generate candidate viewpoints

Unless the user requests a specific number, create 6–8 candidates. Make each one a complete claim rather than a topic label.

Each candidate must answer:

- What common reading of the news misses.
- What underlying mechanism explains the event.
- Who benefits, who pays, or who carries new risk.
- What could happen next if the mechanism continues.
- Why an ordinary reader should care or change a decision.
- What evidence supports the view.
- What reasonable counterargument limits the claim.

## Filter weak viewpoints

Remove any candidate that:

- Merely restates the headline with more dramatic words.
- Is surprising only because it is extreme.
- Uses “everyone thinks” without evidence.
- Confuses possibility with probability.
- Predicts distant outcomes without a causal mechanism.
- Depends on motives that cannot be observed or supported.
- Has no consequence for the intended reader.
- Copies a popular online take without adding a new explanation.

Prefer a modest claim with strong explanatory power over a shocking claim with weak evidence.

## Rank the candidates

Score each surviving viewpoint from 1–5 on:

- Evidence strength.
- Non-obviousness.
- Explanatory power.
- Relevance to ordinary readers.
- Article depth and discussion potential.

Apply a credibility penalty when the view requires many assumptions, strong prediction, or sensitive allegations. Choose the highest-value defensible view, not automatically the most provocative one.

## Produce the answer

Start with a short factual base containing the verified event, date, and unresolved points.

Present the candidate viewpoints in a table with:

1. Rank
2. Core viewpoint
3. What most people may overlook
4. Logic chain
5. Ordinary person's relevance
6. Supporting evidence
7. Counterargument or boundary
8. Credibility risk

Then expand the top three viewpoints with:

- A one-sentence thesis.
- Two natural Chinese title options, one restrained and one sharper.
- A three-to-five-part article outline.
- The key evidence needed for a full article.
- One sentence explaining how to avoid overstating the conclusion.

Link sources close to the claims they support. Clearly distinguish reported fact, inference, prediction, and editorial judgment.

## Write in a credible voice

- Explain the mechanism in ordinary language.
- Use concrete people, decisions, costs, and consequences.
- Avoid empty abstractions, business jargon, and invented consensus.
- Do not use “颠覆认知” or “所有人都错了” unless the evidence genuinely justifies it.
- Avoid fake balance: include the strongest real limitation, not a token objection.
- Leave room for uncertainty when the story is still developing.

When the user chooses a viewpoint and asks for a full article, pass the verified facts, thesis, logic chain, counterargument, sources, and outline to the relevant writing workflow instead of restarting the analysis.
