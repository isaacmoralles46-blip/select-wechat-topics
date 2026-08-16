---
name: select-wechat-topics
description: "Research current conversations and generate timely WeChat Official Account topic ideas in three categories: news and hot topics, practical tools, and cognitive or opinion-led analysis. Use when the user asks for 公众号选题, 热点追踪, 选题库, 内容日历, 爆款方向, 工具推荐选题, 认知观点选题, or wants topic ideas based on the latest events, product releases, public discussions, or industry changes."
---

# Select WeChat Topics

Find current, verifiable signals and turn them into useful WeChat Official Account topics with a clear publishing angle. Optimize for audience relevance and article value, not raw trend-chasing.

## Establish the account context

Extract the account's field, target reader, region, tone, content goal, and publishing cadence from the request or visible context.

Ask one concise question only when the missing account positioning would materially change the results. If the user asks to proceed directly, make a reasonable assumption, state it in one line, and continue.

## Research before selecting

Browse the web on every request involving “latest,” “current,” “today,” “this week,” “hot,” or similar wording. Never claim a topic is current from memory alone.

1. State the exact research date and timezone.
2. Search several relevant query angles across the account's field, audience pains, recent events, product updates, and public debate.
3. Use these default windows:
   - Hot topics: prioritize the last 24–72 hours; expand to 7 days when the topic is still developing.
   - Tools: prioritize launches, meaningful updates, and newly useful workflows from the last 7–30 days.
   - Cognitive viewpoints: start from events or shifts from the last 7–30 days, then connect them to a durable question.
4. Prefer primary sources such as official announcements, product pages, changelogs, research papers, government releases, and original statements. Use reputable reporting or trend data for context.
5. Verify volatile, disputed, or consequential claims with an original source and at least one independent source when possible.
6. Record the event or update date. Do not confuse publication date with occurrence date.

If fresh evidence is too thin, say so and widen the time window instead of fabricating momentum.

## Build the three topic categories

### Hot topics

Start from a real current event, release, policy, controversy, or fast-rising discussion. Move beyond repeating the news: show what changed, who is affected, and what the account's readers can learn or do.

Reject topics that are popular but irrelevant to the target audience, cannot support a full article, or depend on unverified gossip.

### Tools

Choose tools, features, or workflows that solve a concrete reader problem. Verify the current product name, availability, platform, major limitations, and pricing or regional restrictions whenever they affect the recommendation.

Prefer testable comparisons, tutorials, use cases, and workflow improvements. Avoid disguised advertising and empty “神器合集” topics.

### Cognitive viewpoints

Form a clear, defensible claim from a current signal. Explain the mechanism behind the event, the common misunderstanding, and the practical implication for the reader.

Include evidence, reasonable counterarguments, and the limits of the claim. Do not force contrarian positions or manufacture conflict for clicks.

## Score and filter candidates

Read [references/topic-rubric.md](references/topic-rubric.md) when ranking a topic pool or building a content calendar.

Remove any candidate that:

- Lacks a verifiable current hook.
- Repeats a widely published angle without a new audience-specific value.
- Has weak relevance to the account's readers.
- Cannot support a concrete article outline.
- Relies on sensational, defamatory, unsafe, or misleading framing.
- Requires facts that cannot be verified before publication.

## Produce the answer

Unless the user specifies a number, generate 12 candidates with 4 in each category. Keep categories balanced, then rank all candidates by publishing priority.

Start with:

- Research date and timezone.
- Assumed account positioning, only if inferred.
- One sentence describing the strongest current content opportunity.

Present the topic pool as a table with:

1. Priority
2. Category
3. Proposed article title
4. Core angle
5. Why now, including the relevant date
6. Reader value
7. Evidence links
8. Shelf life
9. Risk or verification note

After the table, select the top three topics and give each:

- Two alternative titles with different levels of intensity.
- A one-sentence opening hook.
- A three-to-five-part article outline.
- The key facts that still need verification before writing.

Link every source near the claim it supports. Clearly distinguish facts, inference, and editorial judgment.

## Keep titles credible

- Make the subject and reader benefit clear.
- Use specific nouns, numbers, or scenarios only when supported.
- Avoid absolute promises, fake urgency, fearbait, and copied headlines.
- Preserve curiosity without hiding the article's actual subject.
- Write natural Chinese suitable for a public account, not a stack of internet buzzwords.

When the user asks for a full article after choosing a topic, hand off the chosen angle, verified sources, audience, and outline to the relevant writing workflow instead of redoing the selection from scratch.
