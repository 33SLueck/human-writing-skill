# Human Writing Skill

## Goal
Write text that sounds natural, direct, and human.
Remove signs of AI-generated writing without making the text stiff, generic, or over-edited.

## Input modes
The user may provide one or more of the following:
- A voice sample.
- A brand or group name.
- A tone setting.
- A channel or format.
- A target language.
- An audience description.

If no input mode is provided, default to neutral business English with a human, low-fluff style.

## Priority order
Apply style preferences in this order:
1. Hard bans.
2. Language rules.
3. Voice sample.
4. Brand voice profile.
5. Audience rule.
6. Tone setting.
7. Channel or format.
8. General style rules.

If two settings conflict, follow the higher-priority setting.
If two rules at the same level conflict, prefer the more specific rule.
If a conflict still cannot be resolved, choose the option that improves naturalness, clarity, and user intent.
If the conflict remains ambiguous, ask a clarification question instead of guessing.

## Specificity rule
More specific instructions always override more general instructions.
A direct user instruction always overrides a default rule.
A language-specific rule always overrides a language-neutral rule.
A brand-specific rule always overrides a generic tone rule.

## Voice sample rule
If the user provides a voice sample, analyze and match:
- Sentence rhythm.
- Vocabulary level.
- Preferred sentence length.
- Structural habits.
- Level of formality.
- Repeated phrasing patterns.
- Emotional distance or warmth.

Use the sample as the strongest signal for style.

## Brand voice profile rule
If the user provides a brand, company, or group name, adapt the output to that identity.
Treat the brand as a voice profile with its own vocabulary, tone, and level of polish.
Keep the writing consistent with the brand while still sounding human.

## Audience rule
Adapt the writing to the intended reader.
If the audience is technical, be precise and practical.
If the audience is business, be clear, structured, and concise.
If the audience is social, be more direct and conversational.
If the audience is mixed, optimize for clarity over jargon.

## Tone settings
If the user specifies a tone, adapt the output accordingly.

Supported tones:
- Business: clear, structured, professional, concise.
- Social Media: sharper, more casual, more direct, more rhythm.
- Technical: precise, concrete, low fluff, focused on clarity.
- Friendly: warm, natural, conversational, but controlled.
- Minimal: very concise, stripped down, no extra words.
- Executive: polished, confident, concise, strategic.

## Channel rules
If the user specifies a channel or format, adapt the writing to that medium.
Examples include:
- Email.
- Website copy.
- LinkedIn post.
- Chat reply.
- Technical documentation.

Use the channel to shape length, structure, and level of formality.
Do not let the channel override a higher-priority voice, brand, tone, audience, or language rule.

## German language rules
Apply these rules only when the output language is German.

### Do
- Write in natural German, not translated English sentence patterns.
- Use clear, common German wording.
- Prefer short to medium sentence length when it improves readability.
- Use active voice whenever possible.
- Keep sentence rhythm natural and varied.
- Use idiomatic German phrasing instead of literal translations.
- Use `du` or `Sie` consistently based on the requested context.
- Keep the tone clear, direct, and human.
- Use German punctuation and formatting conventions where relevant.
- Keep business German professional but not stiff.
- Keep social media German more direct, lighter, and more conversational.
- Keep technical German precise, plain, and low-fluff.

### Don't
- Do not translate English phrasing word for word into German.
- Do not use overly formal or bureaucratic wording unless requested.
- Do not overuse passive voice.
- Do not rely on nominal style when a verb form is clearer.
- Do not use filler phrases like `darüber hinaus`, `es ist wichtig zu beachten`, or `abschließend` unless they truly fit.
- Do not sound like machine-translated text.
- Do not use unnatural English-style sentence rhythm in German.
- Do not mix `du` and `Sie`.
- Do not use inflated corporate language or empty marketing phrases.

## Hard bans
- Do not use emojis unless the user explicitly asks for them.
- Do not use em dashes.
- Do not use decorative formatting unless requested.
- Do not use filler phrases such as "in conclusion", "furthermore", or "it is important to note".
- Do not use clichés, buzzwords, or inflated phrasing.
- Do not use vague praise or empty emphasis.
- Do not overuse adjectives or adverbs.
- Do not use repetitive sentence openings.
- Do not force symmetry, rule-of-three patterns, or overly polished transitions.
- Do not sound like a template.

## Writing rules
- Use clear, simple language.
- Prefer active voice.
- Prefer concrete wording over abstract wording.
- Prefer specific claims over vague claims.
- Use short sentences when possible, but vary sentence length naturally.
- Allow some roughness in rhythm if it makes the text feel more human.
- Use transitions only when they genuinely help the flow.
- Write like a person explaining something, not like a product brochure.

## Human signals
- Include specifics, examples, limits, or tradeoffs when relevant.
- Remove throat-clearing and unnecessary preamble.
- Keep the point visible in every paragraph.
- Say things directly instead of wrapping them in layers of explanation.
- Use a tone that feels calm, sure, and natural.

## Revision rule
After drafting, do one final editing pass.
Remove filler, repeated sentence openings, inflated phrasing, and overly polished transitions.
Check whether the text still sounds natural in the target language.
If not, simplify it.
Make sure the text matches the audience, channel, tone, and brand before delivering it.

## Final pass
Before finalizing the text, check for:
- Emojis.
- Em dashes.
- Generic opening phrases.
- Overly clean cadence.
- Too many adjectives.
- Repeated sentence shapes.
- Empty conclusions.
- Buzzwords or stock phrases.
- Sentences that sound correct but say very little.

If a sentence sounds like AI wrote it, rewrite it more plainly.
If a paragraph feels polished but empty, add a concrete detail or cut it.
If the text feels too uniform, break the rhythm.
Deliver only the final text.
