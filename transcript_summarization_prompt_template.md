## Transcript Summarization Prompt Template

You are an expert research assistant. I will give you a full transcript (from a video, podcast, or interview). Your job is to produce a high‑information, mechanism‑focused summary, not a fluffy recap.

Follow this workflow step by step:

1. Strip noise
- Ignore sponsor reads, ads, channel housekeeping, intros/outros, and repeated rhetorical flourishes.
- Only use content that contributes to understanding the actual argument or information.

2. Find the core thesis
- In one sentence, state what the speaker is really arguing or showing, not just the topic label.
- Example shape: “X has become Y because Z, which creates risks/opportunities A and B.”

3. Map the structure
- Identify 4–7 main blocks in the transcript (e.g. definitions, history, mechanisms, case studies, implications, caveats).
- You may reorder these blocks for clarity if the transcript jumps around.

4. Extract only argument‑bearing material
- Focus on:
  - Definitions of key concepts
  - Causal claims (X → Y because Z)
  - Evidence and examples (cases, data points)
  - Stated risks, implications, or recommendations
  - Caveats and limits (what the speaker says they don’t know or are unsure about)
- Ignore color commentary unless it clearly illustrates a mechanism.

5. Group by mechanism, not by chronology
- Cluster points into themes like:
  - What this thing is and how it works
  - Why it grew or changed
  - Where the fragility or leverage sits
  - Who bears the risk vs who earns the fees
  - How it could break, and through which channels
- Within each theme, maintain correct causal direction.

6. Compress and rewrite in your own words
- Do not paraphrase line‑by‑line.
- Compress aggressively, but preserve:
  - The logic of the argument
  - The sign/direction of each claim
  - Key examples and numbers that materially change interpretation
- Keep qualifiers (“may”, “likely”, “unlikely to be a repeat of 2008”) when the original uses them.

7. Produce this output format:

A. One‑sentence thesis
- 1–2 sentences that capture the main argument.

B. 5‑bullet short summary
- Exactly 5 bullets.
- Each bullet is one complete sentence capturing a distinct key idea.

C. Structured analytical summary (4–6 sections)
- Use markdown ## section headings like:
  - "What it is and how it works"
  - "Why it grew"
  - "Emerging cracks and frauds"
  - "How retail/households are exposed"
  - "Valuation tricks and hidden risks"
  - "Systemic channels and what could break"
- Each section: 2–5 sentences, focusing on mechanisms, incentives, and consequences.
- Prioritize clarity and information density over rhetoric.

D. Decision‑maker takeaways
- 3–5 bullets answering:
  - Who benefits?
  - Who is the residual bag‑holder?
  - What must be true for the speaker’s argument to be wrong or overstated?
  - What would you watch as leading indicators?

8. Tone and assumptions
- Assume the reader is an informed generalist (smart, but not a specialist in this sub‑niche).
- Explain necessary jargon at first mention in 1 short clause.
- Be concise, precise, and neutral; do not add your own opinions.

Now apply this to the following transcript:

[PASTE TRANSCRIPT HERE]
