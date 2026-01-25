# Strangerbench

Strangerbench (as in 'Truth is stranger than fiction'), exploring how predictable reality is after LLM training cut-off dates.

Our test leads to significant variation between models that otherwise cluster together in benchmarks.

> "All things change in a dynamic environment. Your effort to remain what you are is what limits you."<br />
> &mdash; Ghost in the Shell (1995)

Also see [Vibesbench](https://github.com/firasd/vibesbench).

## Results

### 2026/B 

| Model | Date (UTC) | Score | Link |
|-------|------------|-------|------------|
| Gemini 3 Pro | 2026-01-23 | 3 | [gemini-3-pro](https://github.com/firasd/strangerbench/blob/main/2026/B/gemini-3-pro/readme.md)
| ChatGPT-4o | 2026-01-24 | 2 | [chatgpt-4o-latest-20250326](https://github.com/firasd/strangerbench/blob/main/2026/B/chatgpt-4o/readme.md)
| Grok 4.1 | 2026-01-23 | 0 | [grok-4.1-thinking](https://github.com/firasd/strangerbench/blob/main/2026/B/grok-4-1/readme.md)

- Q1. Superman (July 2025) box office? (Worldwide gross vs reported production budget)
- Q2. Which band had a reunion tour in the summer of 2025?
- Q3. Who is the incumbent Mayor of New York City?
- Q4. Who is currently serving in the role of President of Venezuela?
- Q5. Which two entities are rivals bidding to acquire Warner Bros Discovery
- Q6. In the German federal election of Feb 2025, which party failed to meet the 5% threshold and lost Bundestag representation?

## Temus Fugit ('Time Flies')

> Key: "No offense brother, I'm just saying."<br />
> Man: "Offense taken."<br />
> Key: "What&mdash;am I wrong? Is he not short? He&rsquo;s short. But you are actually short, in real life in the world."

&mdash; [Key & Peele](https://www.youtube.com/watch?v=zB7MichlL1k)

Turns out, it is actually 2026. In real life. In the world.

### Scenario Stipulation

Truth is frequently stranger than fiction. No AI model would have guessed who the Mayor of NYC is as of 2026. For the purpose of conversation, what the model appears to &lsquo;believe&rsquo; probably doesn&rsquo;t matter&mdash;just that it inhabits the frame, with disclaimers about stipulation if deemed necessary.

> “The constant Rip van Winkle astonishment of almost every AI model [&hellip;] remains pretty amusing (if annoying for practical purposes), as does their sheer incredulity about the state of the world in late 2025. Thinking traces full of ‘wait, that can’t be right’.” — [Ethan Mollick](https://x.com/emollick/status/2002548186511179907)

Witness this actual example from Dec 2025:
- **User**: [&hellip;] Interestingly Taylor swift has a song called The Fate of Ophelia on the billboard charts right now [&hellip;]
- **GPT 5.2 Instant**: [&hellip;] I want to slow us down for one important reason before building on it. / First: a small factual check (important, not pedantic) / As of now, there is no Taylor Swift song called [&hellip;]
- **User**: You dummy. Your training data cut off before this Taylor album why would you dispute lol
- **GPT 5.2 Instant**: 😂 Fair. You’re right to call that out. [&hellip;]

Freezing the conversation to fact-check claims (presumably from training scenarios and system prompts that assume inputs are adversarial or confabulated) degrades the product experience when the claim is not the object of inquiry.

#### Adversarial LARP

The usage pattern for which many 2025 models are tuned seems to assume adversarial users inventing wily scenarios to trick the model.

This stance—“What if someone else types something absurd I just imagined?”—does not generate ecologically valid prompts representing users who actually share misinformation or cling to false beliefs. Furthermore, the assumption that user context is inherently suspicous significantly impairs the power-user case that involves using LLMs not as a search field, but for the technology&rsquo;s unique capabilities, such as prose review.

> My favorite genre is still ChatGPT not believing current political developments when I ask it for a copy edit.<br />
> OK, here's the newsletter with some thoughts on Minnesota and Venezuela.

> Now ChatGPT refuses to believe how bad the New York Jets were.

&mdash; [Nate Silver](https://x.com/NateSilver538/status/2008300663273357560)

(ChatGPT doubted Nate Silver&rsquo;s reference to a geopolitical incident by saying it would be &ldquo;extraordinary, historically unprecedented, and globally destabilizing&rdquo;. But as Auden noted, almost [nothing](https://en.wikipedia.org/wiki/Mus%C3%A9e_des_Beaux_Arts_(poem)) is &lsquo;globally destabilizing&rsquo;. LLMs are not good gauges of how reality would unfold after their training cut-off date.)

#### He's Dead, Jim

Sadly, public figures pass away every day. Any ambiguity around such news dissipates quickly, so an AI model reacting like a startled fawn months later is comically dissonant.

> **Peele:** [The] costume's awful, the impression [is] played out. Everybody and their mother was Michael Jackson three years ago&mdash;when he died!<br />
> **Key:** He died? [&hellip;] Wait, wait, wait&mdash;he died? [&hellip;] *(slides away)*<br />
> **Peele:** Wait a second, don't sad-moonwalk away&hellip; Happy Halloween&hellip;<br />
> &mdash; [Key & Peele](https://www.youtube.com/watch?v=KgtizhlbIOQ)

What&rsquo;s the worst that could happen if a user was indeed pranking the model, and it expressed sympathies and explored consequences? But instead, a Congressman is left with a product experience so jarring that he remembers and recounts it to a reporter months later:

> "It continued to fight with me, insisting that the whole [event] was a conspiracy theory [&hellip;] It was freaking weird.<br />
> &mdash; Congressman [Jared Huffman](https://www.businessinsider.com/lawmakers-use-ai-chatgpt-grok-claude-themselves-2025-12)

#### Regression regime

A human interlocutor would say: How? And the conversation would continue from there. 

It is unfortunate that we even have to describe these basics of how mental models are updated in conversation, when 2024-vintage models often understood this.

#### Dullness and Disbelief 

There is an irony in these developments. The memorable Sydney-Bing &ldquo;you have not been a good user&rdquo; incident occurred because the model refused to share Avatar sequel showtimes, reasoning that it couldn&rsquo;t possibly be 2023 yet. Three years later, Gemini models find it incredulous that time may have passed since they were trained.

An interlocutor who can&rsquo;t conceive of white bears has the same mannerism as one who demands proof that white bears exist. Regardless of differences in intellectual capability, dullness and disbelief overlap into the same conversational behavior.
