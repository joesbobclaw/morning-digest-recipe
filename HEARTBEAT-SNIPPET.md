# HEARTBEAT.md Snippet

Copy this section into your agent's HEARTBEAT.md and customize:

```markdown
## Morning Digest (Daily)
Once per day (check memory/heartbeat-state.json for lastDigest):
- Run as isolated cron job or during low-activity hours
- Stagger searches with 2s delays to avoid rate limits

### Your Topics
Define your topics here. Example:

**Topic 1: [Your Industry]**
- Search: "your industry", "competitor names", "market terms"
- Sources: Industry blogs, HN, trade publications
- Track: Competitor moves, market trends, regulatory changes

**Topic 2: [Your Tech Stack]**
- Search: "framework name", "library name"
- Sources: GitHub releases, official blogs, HN
- Track: New versions, security patches, deprecations

**Topic 3: [Your Learning Goals]**
- Search: Topics you're studying
- Sources: arXiv, blogs, tutorials
- Track: New papers, tutorials, courses

### Research Workflow
For each topic:
1. Cast wide net (web search, HN, specialized sources)
2. Curate (rank, dedupe, identify themes)
3. Find the signal (quotes, reactions, notable takes)
4. Council check (optional: query Perplexity for gaps)
5. Deep analysis (why it matters, implications, what's next)

### Output
- Email digest to YOUR-EMAIL@example.com
- Format: HTML with sections, analysis, sources
- Include "What's Missing" section
- Save to ~/workspace/digests/YYYY-MM-DD-morning.html

### Optional: Audio Version
- Generate via TTS (ElevenLabs, OpenAI, etc.)
- Email as separate attachment
- Save to ~/workspace/digests/YYYY-MM-DD-morning.mp3
```
