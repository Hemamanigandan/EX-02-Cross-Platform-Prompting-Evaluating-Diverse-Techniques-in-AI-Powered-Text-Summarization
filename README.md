# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

## Algorithm
Accuracy
Gemini often takes a slight lead in factual grounding for technical topics, thanks to its tight integration with real-time search and Google's knowledge infrastructure. It tends to anchor explanations in current data (e.g., Ethereum staking stats or PoS adoption trends in 2026) with fewer generalizations. ChatGPT delivers very strong, balanced accuracy — especially in deep reasoning and precise terminology (like explicitly detailing digital signatures or double-spending mechanics) — and remains highly reliable for evergreen concepts without major slips. Grok performs well on quick, contextual facts (particularly if tied to social trends or real-time events via X data), but it sometimes trades a bit of rigor for speed or personality, occasionally introducing more opinionated phrasing or minor imprecision in dense technical recall compared to the other two.
→ Gemini edges out narrowly for fact-heavy technical summaries, followed closely by ChatGPT; Grok trails slightly in strict correctness.

Coherence
ChatGPT stands out here with its polished, logical flow — explanations move smoothly from definition to structure, mechanisms, applications, challenges, and conclusion, feeling like a well-edited textbook section or study note. Transitions are clean and predictable, making it very easy to follow in a linear way. Gemini maintains strong coherence through storytelling — the narrative builds naturally (e.g., "chain reaction" for hashing links) without feeling disjointed. Grok's coherence is solid in conversational bursts, but its charismatic tangents, humor, or witty asides can occasionally interrupt the tight logical thread, making it feel more like an engaging chat than a seamless mini-article.
→ ChatGPT leads for textbook-like logical flow, Gemini is very close with story-driven coherence, and Grok comes third when strict structure matters.

Simplicity
Gemini shines brightest in this area for beginners. Its analogy-heavy style ("digital book of records," "chain reaction," "no central boss") turns abstract ideas like hashing, immutability, and consensus into instantly relatable pictures, reducing cognitive load without sacrificing depth — perfect for undergraduates new to the topic. ChatGPT is clear and accessible but leans more formal and term-heavy at times, which can feel a touch denser for absolute newcomers. Grok keeps things straightforward and avoids unnecessary jargon, often using everyday language or humor to lighten explanations, but the personality flair sometimes adds extra color that isn't strictly needed for pure simplicity.
→ Gemini wins most convincingly on beginner-friendly simplicity via analogies, Grok is strong on approachable language, ChatGPT is solid but slightly more academic.

Speed
All three platforms respond very quickly for text-based summary generation in 2026 — differences are minor and often depend more on server load, model variant, or prompt complexity than inherent design. Grok frequently feels snappiest in casual, back-and-forth interactions (thanks to xAI's optimization for fast conversational replies). Gemini and ChatGPT are neck-and-neck for single-shot outputs like summaries, with Gemini sometimes gaining a hair from its search integration efficiency. No major lag separates them meaningfully for this task.
→ Near tie across all three — Grok might edge it slightly for ultra-quick back-and-forth feel, but practically indistinguishable.

User experience
Grok often delivers the most enjoyable and motivating interaction — its witty, human-like tone, occasional humor, directness, and "companion" vibe make reading feel fun and personal (like chatting with a knowledgeable friend who isn't afraid to be candid). Gemini provides a warm, teacher-like experience: engaging, encouraging follow-ups, and analogy-driven clarity that keeps learners hooked without dryness. ChatGPT offers a highly professional, dependable feel — great for study or reference, but it can come across as more restrained or neutral, lacking the extra spark of personality that boosts stickiness for casual learners.
→ Grok frequently wins on pure enjoyment and rapport, Gemini is very close for educational warmth, ChatGPT excels at reliable professionalism but feels drier.

## Result
In summary for undergraduate-friendly technical explanations like blockchain basics:

Choose Gemini + narrative/analogy style if you want the strongest blend of simplicity, engagement, and solid accuracy to help beginners truly get it and stay interested.

Go with ChatGPT + structured style if maximum coherence, precision, and exam/study-note readiness matter most.


