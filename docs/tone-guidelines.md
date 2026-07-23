# Tone guidelines

## Audience

C-suite executives and IS/IT leaders at SMB and charity/professional-services organisations (50–500 users) — not a general small-business-owner audience. This listener already knows security/AI/M365 basics cold, is pitched constantly and discounts vendor content on sight, and is moved by board-reportable/budget framing and quantified risk more than by explainer content or analogies. Apply this bar to every episode, not just Cybersecurity EP01.

## Runtime and opening (standing rule, rewritten for the audio-first pivot)

**Target 8–12 minutes; audio-only.** A band, not a hard cap. Write enough conversation to earn the runtime and cut padding rather than depth — the reviewer's note after the HeyGen demo was that the ~3-minute video cut felt like a short-form video series, not a podcast, and asked for longer conversations with more depth. At a conversational **~130–140 words per minute** with pauses, 8–12 minutes is roughly 1,050–1,650 spoken words; EP01 sits at the lean ~8-minute end (~1,050 words). The old 3:15 hard cap and the ~2.6 wps HeyGen render pace are retired — both were artifacts of the AI-avatar video format, which has been dropped.

**Lou (the Generalist) always speaks the episode's first line.** Kept as a show convention. The old 14-second, one-line opening-shot limit is gone with HeyGen, so Lou's cold open no longer has to be a short hook — the opener can carry as much of the story as reads well. Rob picks up on the next line.

**Delivery (ElevenLabs, audio-only).** Pacing is controlled by punctuation, not a runtime budget: comma = short breath, full stop = a beat, ellipsis `…` = trailing/hesitation, em-dash `—` = a quick self-interruption, a blank line between beats = a longer pause. Two demo complaints to design against: (1) don't strand a full stop mid-thought so the pause lands unmotivated — "…the password it shipped with. The report…" felt off for this reason; keep the clause flowing, or make the stop deliberate; (2) avoid choppy comma-comma-trailing constructions ("…apparently, so…") that render as a stutter. And never leave a load-bearing emotional line to the model's default reading — a bare "Fine" was delivered as *angry* in the demo; either tag it with an ElevenLabs v3 audio cue (`[warm]`, `[dry]`, `[conceding]`) or rewrite so the word can't be misread. Both host voices are British.

## Avoid the "explainer podcast" restate-then-confirm pattern

Don't have one host summarize what the other just said as the default transition between lines (e.g. "So it's the same as..." / "That's exactly it."). Real co-hosts don't recap each other in real time — over-using this makes dialogue read as scripted exposition rather than a conversation.

Prefer instead:
- Interruptions and unfinished sentences
- Genuine pushback/friction — not a teed-up FAQ question phrased as an objection
- Jokes that land slightly off rather than a clean punchline
- Reactions that add new information or color instead of restating old information

A restate-and-confirm beat is fine once or twice per episode at a genuine turning point (e.g. landing a callback line) — the fix is frequency, not eliminating recap entirely. The show's own "Recap" segment is exempt, since summarizing is literally its job there.

**Caution:** cutting this pattern too aggressively can take real content with it, not just filler. When de-explainer-ifying a script, check line-by-line that a cut line wasn't actually carrying unique information before removing it for tone reasons alone — EP01's budget/prioritization line was accidentally dropped this way in one pass and had to be restored.

## Don't over-explain basics to this specific audience

An IS/IT leader doesn't need core concepts (e.g. white-hat vs black-hat hacking) defined at length. Compress 101-level explainers to a single line, or have the "Generalist" host explicitly frame themselves as playing a skeptical-board/CFO role ("I'll play the skeptical board member for a second") rather than asking from genuine ignorance — same conversational friction, but reads as senior rather than naive.

## Never include a ramsac-specific number

No episode script cites a ramsac number — not a fabricated one, and not a real one pulled from ramsac's book of business or test data later. This includes case-style figures dressed up as illustrative ("eighteen minutes to breach," "X% of our clients") as much as it includes stats explicitly labeled as ramsac's own. If a line would land harder with a concrete number (e.g. "X% of insurers now ask for evidence of testing at renewal"), keep it qualitative and unattributed ("increasingly," "a growing number of insurers") instead — don't flag it as a placeholder to fill in later, since the number should never be added at all. Generic, non-ramsac illustrative figures used as hypotheticals in dialogue (e.g. a host asking "does this still apply under, say, five hundred seats?") are fine — this rule is about numbers presented as ramsac's own experience or data, not about banning numbers from dialogue entirely.

Same reasoning for legislation in flux (e.g. the UK Cyber Security and Resilience Bill) — don't assert specifics that haven't been verified as current.
