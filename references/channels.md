# Channel markers, quick scan and copywriting

Read this file for email, LinkedIn, Slack, blog posts, and product or marketing copy, and whenever the user asks for a review score. The editing contract in `SKILL.md` governs everything here.

## AI-pattern review and originality

The detailed phrase, structure, formatting, and context catalog is in `references/patterns.md`. The Humanizer adds the universal scan and channel checks below. **These are review prompts, not unconditional bans.** Apply the core editing contract before flagging anything.

## Universal phrase and structure scan

### Buzzwords and filler (marketing, product, and social copy)

insights, the key to, success requires, streamline, leverage, optimize, maximize, unlock, unlock potential, unleash, driving impact, enable, empower, solutions-oriented, world-class, cutting-edge, innovative, next-gen, game-changer, best-in-class, future-proof, revolutionary, scalable, disruptive, holistic, robust, dynamic, agile, seamless, synergy

In technical writing several of these are terms of art ("robust estimator", "scalable architecture", "dynamic typing", Agile as a named process). There the tiered word tables and the technical-blog exceptions decide; this list doesn't override them.

### Marketing Clichés - Avoid

customer-centric, growth hacking, data-driven (when filler), actionable insights, move the needle, low-hanging fruit, quick wins, win-win, thought leader, best practices (unless citing research), at scale (without numbers), paradigm shift, digital transformation, value-add

### Stylistic defaults (review prompts, not bans)

These are defaults for prose you write and candidates to review in prose you edit. The editing contract and each catalog entry's pass conditions decide whether a match becomes an edit.

- No em dashes (see Punctuation and mechanics in `SKILL.md`).
- No corporate filler such as "as per our learnings."
- No exaggerated symbolism.
- Review runs of three or more same-shape fragments used as punchlines ("More X. More Y. More Z."). One fragment that lands a point is rhythm; see Manufactured punchlines and staccato drama in `references/patterns.md`.
- Review three or more consecutive sentences that open on the same word when the repetition isn't doing rhetorical work; see Same-opener sentence runs in `references/patterns.md`. Two in a row is not a finding.
- No generic template hooks and no moralizing tone.

### Be specific with what the source has

Prefer the concrete details the source already supplies: names, numbers, examples, trade-offs, cause and effect. If a sentence stays vague because the source is vague, flag the gap; never invent the detail. Specific is not the same as over-precise: keep the precision the point needs, and round off detail that only proves you checked (see the baseline in `references/conversational.md`).

### Sound like a person

- Write as if explaining something to a smart peer.
- Let sentence rhythm follow the content. Vary it where it has become accidentally monotonous; there is no quota of short or long sentences.
- Avoid polished "punchline" energy.
- Keep the author's own rough edges where they work. Never add new ones (typos, fragments, slang) to look human; see Never inject these in `SKILL.md`.

### Make it operational

Explain mechanics, show how something works, call out trade-offs, and reduce uncertainty, all within what the source supports. Give readers something they can use, not inspiration.

### Default tone for new drafts

When no voice is given and the source doesn't establish one: calm, pragmatic, no hype, no preaching. Don't impose this on text that already has its own voice. For editorial prose, avoid wording that sounds like generic SaaS homepage copy. Product copy has a different job, but it still needs specific claims and real evidence.

---

### Universal phrase-level markers

- Overused transitions: "Furthermore", "Moreover", "In conclusion", "Additionally", "It's worth noting", "in summary" (especially mid-post to signal a list is coming - just give the list)
- Hollow intensifiers: "incredibly", "truly", "genuinely" and the like when they add emphasis instead of information. "Crucial" (Tier 2) and "significantly" (Tier 3) follow their tier thresholds.
- AI vocabulary: use the tiered word tables in `references/patterns.md` (Tier 1A, 1B, 2 and 3) with their thresholds and context exceptions. Don't flag a word because it "sounds like AI" if it isn't in those tables: ordinary words such as "typically", "various", "overall", "certainly", "essentially", "whilst" or "albeit" are not findings by themselves. A few phrase-level candidates outside the tables: "journey" and "superpower" as metaphors, "reality" as a dramatic reveal ("The reality? …"), and "Absolutely," as an affirmation opener (see Chatbot artifacts in `references/patterns.md`).
- AI phrasing & metaphors: "brutal clarity", "lost the plot", "painfully clear", "blunt honesty", "that way you can", "with precision", "lived experience", "launching a new chapter", "the energy in the room", "laying the groundwork", "Here's to [noun]!", "will never be the same", "that promise becomes reality", "ends the era of", "the same tension", "keeping my hands dirty", "here's a breakdown" (AI's default phrase before introducing a list or explanation - cut it, just give the breakdown), "in the ever-evolving landscape" (a grandiose variant of "In today's [noun]" - both are filler openers that add no information), "a testament to" (AI affirmation phrase that gestures at quality without specifying anything, e.g. "This is a testament to the team's hard work" - say what the team actually did), "there is a specific kind of [magic/energy/power] that happens when" (vague wonder-framing that signals nothing concrete, e.g. "There is a specific kind of magic that happens when a Zoom square finally becomes a person" - describe the actual experience instead), "Below is..." / "Below:" as a list introduction (AI list-pivot tell - e.g. "Below is a breakdown of the key steps:" - cut the intro, start the list), "such as" used repeatedly to introduce examples (AI exhausts this connector when listing evidence; vary with specific names, numbers, or just name the thing directly)
- AI phrasing & metaphors (continued): these are phrases AI uses to simulate directness, enthusiasm, or authenticity. They feel punchy but are recycled across AI outputs. Replace with language specific to the author's actual voice.
- Stacked abstract noun lists: listing 3+ abstract nouns for emotional weight (e.g. "creativity, passion, joy and drive"). Replace with a concrete claim or cut to one noun.
- Passive voice constructions where active would be stronger
- Hedge phrases: "It's important to note that", "One might argue", "It goes without saying"
- Filler openers: "In today's [noun]", "When it comes to", "At the end of the day", "The truth is" (front-loads candor before a generic claim - e.g. "The truth is, most managers don't know how to have hard conversations" - just state the claim; distinct from "And I'll be honest:" which is a mid-sentence pivot)
- Product-tagline phrasing in non-product contexts: compact phrases that read like feature copy instead of a person talking (e.g. "Hands-free until review", "Built for scale")
- Runway sentences: vague hype lines before the actual specific detail. Cut the runway, start with the substance.

---

### Universal structural markers

- Opens with a generic claim when the source has a more specific point, story, or example that could lead. Don't invent a story or a contrarian take to fill the slot (see Never inject these in `SKILL.md`).
- Uses bullet-point structure where prose would carry more weight
- Follows the intro > 3-point list > conclusion template
- Closes by restating what was just said. Cut the recap and end on the last real point; don't swap in a challenge, principle, or question the source doesn't contain.
- Every paragraph is roughly the same length and the boundaries don't follow the argument (see Rhythm and uniformity in `references/patterns.md`; not a finding when the genre calls for regular structure)
- Stacked fragment cadence used as punchlines: "X. Y. Z." format. Rewrite as a real sentence.
- No concrete example, data point, or firsthand experience anywhere in the content
- Three-part parallel structure: "It's not about X. It's about Y. It's about Z." Rewrite as a single direct sentence.
- Colon-list pattern: introducing a list mid-sentence with a colon where prose would read more naturally. If the list has fewer than four items, write it as a sentence.
- Contrast-based negation constructions: "It's not X. It's Y.", "This isn't about X. It's about Y." Rewrite as a positive statement when nobody raised X; keep a real correction whose halves both carry information (see `ec-supported-contrast` in `references/patterns.md`).
- Exclamation-point inflation: AI adds enthusiasm via exclamation marks where the content doesn't warrant it. Remove or replace with periods.
- Adverb-stacking pivot formula: "X matters. Y matters. But that's not the point. The point is Z." Rewrite as a single declarative sentence.
- Declarative simplicity setup: "The answer is straightforward:" - cut the setup, start with the substance.
- Self-posed question as transition: "Why? Because..." Rewrite as a declarative statement.
- Declarative reveal pattern: "The skill that will separate...? It's critical thinking." Just state the claim directly.
- Label-colon framework: packaging observations into named label: description pairs to simulate a framework. Unless documenting a real methodology, write in prose.
- Stat bomb opener: rapid-fire sequence of 3+ short statistical fragments. Weave stats into real sentences.
- Honesty disclaimer: "And I'll be honest:", "I'll be real:" - just state the opinion directly.
- Credential stacking opener: stacking 2-3 credential statements before giving advice. Weave credentials into the argument or skip them.
- Definition reframe: redefining a problem in a pithy formula (e.g. "It's an execution problem dressed up as a leadership problem."). State the observation without clever packaging.
- Punchy orphan closer: ending with a standalone short sentence as a mic-drop. Close with a real thought or fold it into the final paragraph.
- Tension-colon opener: opening with a colon-separated tension statement. Just state the observation.
- Parenthetical aside for fake candor: multiple parenthetical asides to simulate conversational tone. One is fine. Multiple signal performative writing.
- Standalone hype fragment: "This is big." or "Game changer." Cut or replace with a specific claim.
- Triple rhetorical question hook: opening with 2-3 rapid rhetorical questions to manufacture intrigue. Rewrite as a direct opening, or open on a specific story the source already has.
- Reading complexity creep: AI clusters multi-syllable vocabulary and nested dependent clauses. The source Humanizer claims above-10th-grade text receives ~35% less reach on LinkedIn, but treat that figure as unverified unless independently checked. As a writing test for conversational and social prose (not docs, technical, or legal text, where the precise term wins), flag: three or more 3-syllable words in the same sentence, or sentences with 2+ embedded dependent clauses. Rewrite with shorter words, shorter sentences. Aim for a 7th–9th grade reading level in conversational professional content.

---

### LinkedIn-specific markers

**Phrase-level:**
- LinkedIn pivot transitions: "But here's the thing", "And here's the kicker", "Here's what most people miss", "Let me explain", "Here's why that matters"
- Engagement bait closers: "Agree?", "Thoughts?", "What would you add?", "Drop a comment if you've experienced this", "Repost if this resonates" - if the post is worth engaging with, people will. Don't beg for it.
- Vulnerability performance phrases: "I'll be honest", "Can I be real for a second?", "I'll be vulnerable here", "I wasn't going to share this but..." - real vulnerability doesn't announce itself.
- Fake humility: "I'm no expert, but...", "I don't have all the answers, but...", "This might be controversial, but..." - these always precede confident claims. Skip the disclaimer.
- Tag-and-thank: tagging 5+ people at the end with "Shoutout to..." - one or two genuine tags are fine. A list is reach-farming.
- Dream-realized language: "I realized my dream", "A dream come true", "Pinch me moment" - describe what happened and let readers judge.
- Arrow chain format: using → arrows to show a process/flow. This reads as a slide deck. Write it as a sentence.
- ALL-CAPS single-word injection: capitalizing individual words mid-sentence to simulate spoken intensity or excitement. Example: "We've onboarded HUNDREDS of customers. Generated MILLIONS in ARR." or "Woke up to a VERY exciting email." Reads as performative hype. Earn the emphasis through specificity - use the actual number, the actual thing - instead of a shouted word.
- "What if I told you..." curiosity hook: is a recognized ghostwriter/AI template. The source claims it increases "see more" clicks 30-40%, but that figure is unverified unless independently checked. When the payoff is generic, the reader feels cheated. Only valid when followed by a specific, non-obvious insight the author genuinely has. If the post could have been written by anyone with a search engine, cut the hook and start with the actual claim.
- "Here's what nobody tells you about..." insider framing: signals genuine access or experience, but AI uses this formula constantly without any actual insider knowledge to follow. Flag when the content underneath is generic enough that anyone could have written it. The frame needs to earn itself - what specifically did the author observe that others haven't said?
- "Read that again." / "Let that sink in." permission phrases: dropped after an unremarkable observation to manufacture gravity. The source reports a 22x frequency in AI-generated posts, but treat that figure as unverified unless independently checked. Example: "Your habits shape your identity. Read that again." or "Every setback is a setup for a comeback. Let that sink in." The insight doesn't earn the dramatic pause - cut both.
- "And honestly?" fake candor opener: AI drops this before a non-controversial claim to simulate real-talk authenticity. Example: "And honestly? That's what separates the good from the great." Just state the opinion directly.

**Structural:**
- One-line paragraph formatting: every sentence is its own paragraph. This is LinkedIn's #1 AI/ghostwriter tell. Group related sentences into real paragraphs.
- Hook > 3-point list > mic-drop closer template
- Explaining the algorithm: telling people why to comment or share ("Gets it into more feeds"). Just ask.
- Vulnerability bait hook: opening with a personal failure story designed primarily to hook readers, then pivoting to a tidy lesson. If the story is real, let it be messy.
- "We didn't just build X. We built Y" negation upgrade: negating one thing to claim a grander version. Just say what you built.
- Hyperbole opener: "X will never be the same." or "Everything changed." Start with the specific thing that happened.
- Common-belief-then-counter opener: three-sentence setup that states a common belief as fact, attributes it to "most people," then knocks it down (e.g., "Zapier is for simple workflows. That's what most people think. And they're dead wrong."). This is a ghostwriter/AI template for manufacturing tension. Rewrite by starting with the actual insight directly.
- Period-separated word emphasis: using periods between individual words to simulate spoken intensity (e.g., "every. single. day." or "This. Is. The. Moment."). Reads as performative. Use normal sentence rhythm or rewrite the sentence to earn the emphasis.
- Self-intro paragraph at post bottom: ending a milestone or story post with a formal self-introduction paragraph ("My name is [X] and I'm a [title]. Outside of [work], I'm fascinated by [hobbies]. I'm a [credential1], [credential2], and [credential3]."). This is an AI/ghostwriter template habit. Either cut it or weave the relevant credential into the post body where it earns context.
- Information-withheld hook: opening 1-2 sentences that deliberately omit the post's actual subject to force the "...more" click. The reader cannot tell what the post is about without expanding it. Example: "At Netflix, we had 1 UNSPOKEN rule. It was about this 1 word." This is pure curiosity-gap manipulation - it promises information without delivering any. Rewrite by opening with the actual insight: state the rule, then explain why it mattered.
- "X is [positive]. [X variant] is a whole different game" contrast formula: a two-sentence template that praises the easy version of something, then implies the real version is harder/more serious. Example: "Prompt-to-prototype is magical. Prompt-to-production is a whole different game." Sounds punchy but is a recycled structure. Collapse into a single direct sentence about the actual challenge.
- Cliché proverb opener: starting a post with a well-worn business maxim as the hook. Example: "Work smarter, not harder." These require no original thinking and signal that what follows will be generic. Replace with the specific observation or experience that prompted the post.
- External link CTA ending: closing a post with an external URL in the body, or "link in comments 👇", is claimed by the source to cut reach by approximately 60%, but that figure and the algorithmic explanation are unverified unless independently checked. Avoid using the CTA as a default template; do not promise a specific reach penalty. If sharing a resource, omit the link from the post entirely and add it in the first comment after engagement begins - or better, just describe what's there and let people find it.
- Achievement post formula: AI-generated milestone posts follow a consistent 4-beat template: (1) emotion word + announcement, (2) team/supporter thanks, (3) generic universal lesson, (4) emoji-closed enthusiasm sign-off. Example: "Thrilled to announce [Company] just hit [milestone]! 🎉 Couldn't have done it without my incredible team. The biggest lesson: consistency wins. Excited for what's next! 🚀" Flag when all four beats appear in sequence with generic language throughout. Replace with a specific story about what made this milestone hard, surprising, or meaningful.
- Fake dialogue/conversation format: framing an opinion piece as a fabricated back-and-forth between two roles (CEO/CMO, Founder/Investor, Manager/Employee, Recruiter/Candidate). Example: "CEO: Why do we separate brand and performance? CMO: Because they're different things. CEO: How so? CMO: [generic insight]." AI uses this structure to simulate authority and lived experience without firsthand evidence. The format is a ghostwriter/AI template for laundering an opinion as a conversation - rewrite as direct prose with the actual argument stated up front.

---

### Email-specific markers

**Phrase-level:**
- AI greeting formulas: "I hope this email finds you well", "I trust this message finds you in good spirits", "Hope you had a great weekend" (when the sender doesn't know the recipient)
- AI closings: "Please don't hesitate to reach out", "I look forward to hearing from you", "Thank you for your time and consideration", "Warmest regards", "With gratitude"
- Corporate filler: "I wanted to reach out because...", "I'm writing to inform you that...", "Per our previous conversation", "As per my last email", "Going forward", "At your earliest convenience", "Please be advised"
- Fake personalization: "I noticed your company is doing great things in [industry]", "I was impressed by your recent [post/talk/article]" - if you can't cite something specific, delete the flattery
- Hedge language: "I was wondering if perhaps...", "Would it be possible to maybe...", "I just wanted to quickly check if..."
- Email AI vocabulary: "circle back", "loop in", "touch base", "sync up", "deep dive", "bandwidth", "on my radar", "double-click on", "unpack"
- Over-politeness stacking: multiple politeness phrases in one email. One "thanks" is enough.
- Rhetorical throat-clearing: "I'd be remiss if I didn't mention...", "It goes without saying that..."
- Subject line AI patterns: "Quick question", "Following up", "Checking in", "A thought", "[First name], quick thought" - be specific about what the email is about

**Structural:**
- More than one ask in the email. Good emails have one clear ask.
- Ask buried at the bottom. Lead with what you need.
- Email can be longer than its purpose requires. The source uses “2-3x” as a rule of thumb, not a measured universal ratio.
- Opens with context the recipient already knows.
- Greeting mismatched to the relationship ("Dear Mr. Smith" for someone you've emailed 20 times).
- Vague CTA instead of specific ("Let me know if you'd like to chat sometime" vs "Free Tuesday at 2pm?").
- Email reads like a template with blanks filled in.
- Multiple sign-off phrases stacked.
- "PS:" line that's obviously the real pitch.

---

### Slack-specific markers

**Phrase-level:**
- Over-formal language for Slack context: "I wanted to reach out regarding...", "Please be advised that...", "At your earliest convenience" - Slack is casual. Write like you talk.
- Corporate Slack filler: "Just wanted to flag...", "Wanted to surface this...", "Looping in [name] for visibility" - be direct about what you need.
- Unnecessary hedging in a fast medium: "Sorry to bother you, but...", "I might be wrong, but...", "Not sure if this is the right channel, but..." - just say it.
- Emoji overload: 3+ emoji in a short message to manufacture enthusiasm or soften a request.

**Structural:**
- Message is too long for Slack. If it needs more than 4-5 sentences, it should probably be an email, a doc, or a thread with a TL;DR at the top.
- Buries the ask or action item in a long message. Lead with the ask, then provide context.
- Uses formal structure (greeting + body + sign-off) in a Slack message. Just say the thing.
- Over-explains context that the channel audience already has.

---

When producing a requested audit report, list every justified finding with the exact quote and enough location context.

---

## Originality and audience-value checks

### Step 2: Originality Check

Evaluate whether the content contains thinking that is specific to the author or could have been written by anyone with a search engine. Flag:

- Advice that any content marketer / consultant could write without domain expertise
- No firsthand experience, customer story, or specific evidence
- Recycled industry framing ("the future of X is Y")
- Making the same point twice without adding depth
- Missing the "only I could write this" factor - no earned authority on display
- Generic examples instead of specific ones from the author's experience

**LinkedIn-specific originality flags:**
- The post is a thinly disguised product plug dressed as a "lesson learned"
- The post uses a personal story but the takeaway is generic enough to be a fortune cookie

---

### Step 2b: Hook vs. Value Calibration (LinkedIn only)

The following two-stage description is the Humanizer source's editorial model, not a verified account of LinkedIn's current ranking internals. Use it to reason about attention versus reader value, not to promise distribution outcomes.

**Stage 1 - Initial attention (the source describes the first 30-60 minutes):**
The hook quality determines whether the algorithm distributes broadly. A good hook forces a "see more" click. Stage 1 is won or lost in the first 2-3 lines.

**Stage 2 - Continued distribution (ongoing):**
Dwell time, saves, and substantive comments determine whether the algorithm keeps distributing. This is where AI content collapses. Generic content has low dwell time (reader finishes in 8 seconds, moves on), low saves (nothing specific enough to come back to), and shallow comments ("Great insight!" not a real reaction).

The source claims one save is worth 5x a like and substantive comments deliver a 2.4x reach boost, but these multipliers are unverified unless independently checked. As an editorial test, ask whether the post contains something useful enough to save or a claim worth discussing.

#### Hooks that clear Stage 1 AND earn Stage 2:
- **Specific consequence opener**: opens with a named result, not a lesson. "I lost my best employee yesterday." Not "Here's why retention matters." The specificity signals there's a real story underneath.
- **Data point with personal stakes**: a number + what it meant to the author. "Our conversion dropped 40% in one week. Here's what I found." Not a stat bomb - one number, your reaction to it.
- **Contrarian claim with named evidence**: a direct challenge to a common belief, backed by a specific experience or observation only this author could have. Not "most people get X wrong" - that could be written by anyone.
- **Story that ends unresolved**: a real situation with no tidy lesson. Readers stay to process, comment to add their own read on it.

#### Hooks that game Stage 1 but kill Stage 2:
- **Information-withheld hook** (already flagged above): manufactures curiosity, delivers nothing specific. Reader clicks, reads a generic post, dwell time is 8 seconds.
- **"What if I told you..." / "Here's what nobody tells you..."**: recognized templates. When the payoff is generic, reader feels cheated. Low saves.
- **Triple rhetorical question**: reader already knows this pattern. Skims to find the answer. If the answer is also generic, they're gone.
- **ALL-CAPS intensity signals**: gets initial scroll-stop attention, but if content underneath is hollow, dwell time collapses.
- **Cliché proverb opener**: "Work smarter, not harder" - no curiosity gap, no reason to click "see more."

#### The saves-worthiness test:
Ask: is there one specific, referenceable piece of information in this post - a named tool, a concrete step, a number with context, a named decision the author actually made - that someone would save to return to? AI posts almost never pass this test because the information is general enough to recall without saving. If the post has nothing save-worthy, it won't compound in distribution.

#### The comment-quality test:
Ask: does this post contain a claim specific enough to disagree with, a tradeoff with no obvious right answer, or a story that ends without a lesson? Those generate substantive comments. Generic takeaways generate "So true!" which the algorithm now treats as weak engagement signal. Engagement bait CTAs ("Agree? Drop a comment 👇") are flagged as spam behavior and actively hurt distribution.

**Email-specific: run Clarity & Effectiveness Check instead:**
- Is the purpose clear within the first two sentences?
- Is there exactly one clear ask?
- Could the recipient respond in under 60 seconds?
- Is anything ambiguous that could cause a back-and-forth?
- Does the email give the recipient an easy way to say yes?
- Is the tone appropriate for the relationship and context?
- Is the length right for the purpose?

---

## Optional review scoring

Use scores only when the user asks for a review/report or when scoring will materially help. Never imply that a score is an AI-authorship probability.

### Step 3: Score the Content

Score on four dimensions (1–10 scale). **Dimensions vary by content type:**

**Blog Post & LinkedIn:**

| Dimension | What It Measures | Target |
|-----------|-----------------|--------|
| **AI-Likeness** | How much AI texture the content has (lower is better) | 1–3 |
| **Authenticity** | How unmistakably it sounds like a specific human | 8–10 |
| **Reader Value** | Would the target audience find this non-obvious? | 7–10 |
| **Domain Credibility** | Does it require specific background/experience to write? | 7–10 |

**Email:**

| Dimension | What It Measures | Target |
|-----------|-----------------|--------|
| **AI-Likeness** | How much AI texture the email has (lower is better) | 1–3 |
| **Authenticity** | How much it sounds like a real person writing to this specific recipient | 8–10 |
| **Clarity** | Is the purpose clear and the ask unambiguous? | 8–10 |
| **Appropriate Tone** | Is the formality level right for this relationship and context? | 8–10 |

**Slack:**

| Dimension | What It Measures | Target |
|-----------|-----------------|--------|
| **AI-Likeness** | How much AI texture the message has (lower is better) | 1–2 |
| **Naturalness** | Does it sound like how this person would actually type in Slack? | 8–10 |
| **Clarity** | Is the point/ask immediately clear? | 8–10 |
| **Brevity** | Is it the right length for a Slack message? | 8–10 |

Provide a one-sentence justification for each score.

**Important:** If AI-Likeness is low but Domain Credibility (blog/LinkedIn) or Clarity (email/Slack) is also low, call this out explicitly. The content is clean but hollow.

---

### Platform-metric caution

The source Humanizer includes numerical claims about saves, reach multipliers, distribution penalties, “see more” clicks, reading complexity, and algorithmic behavior. They are **unverified source-pack claims**, not settled facts. Do not repeat them as factual platform guidance unless separately validated against current, reliable sources. Use the qualitative editorial tests above without promising a platform outcome.

## Channel-specific rewrite rules

**Apply channel-specific rewrite rules based on detected type:**

**Blog/article rewrite rules:**
- Preserve heading structure unless restructuring is requested; improve generic headings when useful
- Avoid repetitive paragraph lengths when they are accidental, but do not enforce a quota
- Replace "In this article" or "Let's dive in" meta-commentary when it adds no value

**LinkedIn rewrite rules:**
- Keep the post focused and proportionate to its purpose. Do not impose a fixed character target unless the user asks for one or a current platform limit has been verified.
- Don't stack hashtags at the bottom. Weave 1-3 naturally or drop them.
- Remove engagement bait closers entirely.
- Replace arrow-chain formats with real sentences.
- Group related sentences into meaningful paragraphs when one-line-per-sentence formatting is mechanical. Two to four sentences can be a useful guide, not a quota.
- Remove emoji used as decoration. Keep only emoji that carry genuine meaning.

**Email rewrite rules:**
- Lead with the ask or purpose, not context.
- Cut to minimum length. The source uses “2-3x too long” as a rule of thumb, not a measured universal ratio. Trim to the email's purpose without dropping necessary context.
- Match formality to the relationship.
- Use a specific CTA ("Free Tuesday at 2?" not "Let's chat sometime").
- One ask per email.
- Remove performative politeness. One "thanks" is enough.
- Subject line: make it specific to the content.
- Opening: skip "I hope this finds you well." Start with the point.
- Closing: pick one sign-off. Not a stack of three.

**Slack rewrite rules:**
- Usually keep it to 4-5 sentences. If a longer explanation is needed, consider a thread or document rather than cutting useful context.
- Lead with the ask or action item.
- No formal greeting or sign-off.
- Match the casual tone of the channel.
- If sharing a link, add one sentence of context, not a summary.

### Additional genre notes

- **Blog/article:** preserve the existing heading structure unless restructuring is requested; replace generic meta-intros such as “In this article” and “Let's dive in” only when they add no value. A formal or technical piece may correctly use continuous prose and uniform terminology.
- **LinkedIn:** density and audience fit matter more than chasing a character target. Preserve actual story details, use hashtags sparingly when useful, remove engagement bait, write arrows as real sentences when they are only decorative, and combine one-line paragraphs into meaningful groups when the formatting is mechanical. Do not impose a universal character limit as if it were a platform rule.
- **Email:** put the purpose or ask early, keep one primary ask, make the reply easy, match formality to the relationship, and remove redundant greeting/closing formulas. Do not strip necessary context or courtesy when the relationship calls for it.
- **Slack:** lead with the action or question, match the channel's register, avoid email-style sign-offs, and keep it short enough for the discussion. If a message needs a longer argument, use a document or thread with a clear lead.
- **Developer conversations:** reviewer comments should point to the change and make a concrete ask; author replies should acknowledge the valid point before explaining what remains and why; investigation reports should lead with the verdict, then the mechanism. Keep distinct points in separate short paragraphs.
- **Code comments:** explain intent, constraints, ordering, invariants, or non-obvious behavior. Prefer a compact working note over essay-style comments. Never use this skill to rewrite executable code unless the user explicitly requests code changes.
- **Commit messages:** follow the repository's existing prefix and capitalization convention. Describe the user-visible change or problem fixed, not a slogan or a paraphrase of implementation details. If a body is needed, keep it to one or two sentences about why.

## Accuracy-first copywriting

Apply these rules to product copy, landing pages, sales material, announcements, FAQs, testimonials, and any text that makes a claim on behalf of a person or organization.

- **Evidence before claims.** Every number, statistic, performance claim, security/compliance claim, testimonial, named customer, credential, feature, and promise must come from supplied or verified information. If no evidence exists, remove the claim or mark a placeholder explicitly. Empty is better than deceptive.
- **No fabricated social proof.** Never invent customer names, job titles, reviews, quotes, company logos, or results. If there are no real testimonials, don't create a testimonial section.
- **Specific beats generic.** Prefer a concrete capability, audience, outcome, constraint, or trade-off to “revolutionary,” “world-class,” “next-generation,” “seamless,” or “best-in-class.” Show the benefit and its mechanism when the source supports it.
- **CTAs name the action.** Avoid generic defaults such as “Get Started,” “Learn More,” “Try Now,” “Explore,” and “Discover” when a more specific action is known. Prefer an accurate action such as “Watch the demo,” “Create an account,” or “Start a free trial” only when those actions actually exist.
- **No filler FAQ.** Include questions that address real audience concerns. If those concerns are unknown, ask for evidence, use labeled placeholders, or omit the section.
- **No fake personalization.** Don't flatter a recipient or customer with claims about their work unless the writer has supplied a real, specific reason.
- **Content must earn its structure.** Do not force a three-step process, three benefits, a feature grid, a story arc, or a neat moral just because the format is common.
- **Every line has a job.** Copy should clarify what is offered, who it is for, why it matters, what it costs or requires, or what happens next. Remove a section or slogan that does none of those things.

These rules are adapted from the copywriting and evidence rules in [anti-slop](https://github.com/miqdadbadjuber/anti-slop). Its UI-only implementation rules are outside the scope of a writing skill and are not reproduced here.
