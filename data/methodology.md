# Methodology

## How Murmure Scores Community Sentiment

Each tool is scored weekly on a **1–10 scale** based on signals collected from:
- Reddit (r/programming, r/webdev, r/MachineLearning, tool-specific subreddits)
- Hacker News (Show HN, Ask HN, comment threads)
- Twitter/X (mentions, threads, replies)

## Scoring Formula

**Sentiment Score = (Positive Signals − Negative Signals) / Total Signals × 10**

Weighted by:
- Signal recency (last 7 days weighted 2×)
- Engagement volume (upvotes, replies)
- Source authority (top-level posts weighted higher than comments)

## What We Track
- Feature complaints and praise
- Pricing sentiment
- Reliability/uptime mentions
- Competitive comparisons
- Support quality mentions

## Signal Counts
`signal_count` = total posts/comments analyzed that week for that tool.

## Update Frequency
Data is updated every Monday morning.

## Full Reports
For deep-dive analysis including verbatim quotes, complaint clusters, and competitive framing, see [murmure.cc](https://murmure.cc).
