# Fiction

Read this file when the text is a story, a scene, a script, or fan fiction: dialogue lines, named characters acting, past-tense narration, scene breaks. For fiction it overrides the tolerance matrix in `references/patterns.md`. The editing contract in `SKILL.md` still governs everything; in a story, the author's voice and the story's own facts are what it protects.

Fiction differs from the prose the catalog was built on in two ways. It uses several of the catalog's tells on purpose, so those rules relax. And it has tells of its own that no word list catches, because every word in them is ordinary.

## What changes from the catalog

| Catalog rule | In fiction | Why |
| --- | --- | --- |
| Manufactured punchlines and staccato drama | Judge a run of short beats by its scene: a fight, a shock, or a hard cut can earn one. Flag it only when most scenes end on the same beat. | Short beats are a pacing tool. The tell is the same beat everywhere. |
| Same-opener sentence runs | Keep a run that builds, such as a character's spiralling thought or a list of actions. Flag one that is accidental. | Avoid AI Writing's counts on HAP-E found runs of three seven to nine times as often in human text as in GPT-4o output (Llama 3 used them more than the humans). |
| "It's not X, it's Y" and negation chains | Keep them when a character or the narrator corrects an expectation someone in the story holds. Flag them when nobody in the story held X. | A correction inside the story is drama; a correction of nobody is padding. |
| Stranded auxiliary contrast, colon into a triple | Flag only by density across the whole piece. | Both are ordinary sentence shapes, and the same counts found the auxiliary contrast more often in human text than in model output. |
| Subjectless fragments, rhetorical questions, hedging | Skip them in dialogue and in a character's thoughts. Use judgment in narration. | People talk and think in fragments and doubt. |
| Rhythm and uniformity, uniform paragraph length | Judge rhythm by the scene: short in a chase, long in a lull. Flag sameness only when it ignores the scene. | A story's rhythm follows its events, not an argument. |
| Word tiers | Apply them in narration. In dialogue, keep any word the speaker would use. | A character can say "robust"; in narration, "tapestry" is the narrator's choice, and the catalog's reasons apply to it. |
| Em dashes | The rule in `SKILL.md` holds: none in English prose. Break off speech with an ellipsis or recast the line. Russian dialogue dashes are required punctuation. | The rule is about punctuation, not genre. |

Every other catalog rule applies to narration as written, and to dialogue only where the speaker would not plausibly talk that way.

## Tells fiction adds

Each check is keyed to a shape you can see. A match is a candidate, not a verdict: the gates in `SKILL.md` still decide.

### Stock comparisons

- **Trigger:** a comparison with "like", "as", or "as if" whose image you have met many times: smelled like a grave, went into her like a nail, came off her like a dropped coat, drew in like a held breath, silence like a blanket, cold as ice.
- **Check:** could the comparison move unchanged into someone else's story?
- **Fix:** cut it, or flag it in detect mode. In a rewrite, replace it only with an image the story already supplies: its setting, its objects, what this narrator would know. Don't stack a second comparison to rescue the first.
- **Why:** each word in a stock comparison is ordinary, so the word lists never fire. The tell is the familiar pairing.

### A character explained beside a scene that shows it

- **Trigger:** a sentence stating a trait or a rule of a character ("She did not fight people. She persuaded them.") next to a scene that shows the same thing.
- **Check:** does the scene already show it?
- **Fix:** cut the statement and let the action carry it. Keep it when the scene can't show it, or when the narrator's voice is the point.
- **Why:** it does the reader's inferring for them. It is the fiction form of the catalog's example restatement.

### A scene that ends on its moral

- **Trigger:** a closing line that names what the scene meant: "It was a lesson in patience.", "Some debts can't be repaid."
- **Fix:** cut it, or end on the last action or image. Keep it if it adds a fact the scene did not show.
- **Why:** it is the same move as the catalog's example restatement and generic conclusions.

### A summary where the scene should be

- **Trigger:** a sentence that compresses the story's main event into a report: "They kept that up for a long time.", "The fight lasted hours."
- **Check:** is this the event the reader came for?
- **Fix:** flag it, in detect mode and in rewrites alike. Expanding it means inventing events, which only a request for new writing allows.
- **Why:** the skill can't write a scene the author didn't, but it can point to where one is missing.

### Canon claims in fiction set in an existing world

- **Trigger:** a sentence that states how the source world works (a creature's habits, a rule of its powers, an institution's procedure) rather than what happens in this story.
- **Check:** does the source say so? Invented events are the point of fan fiction. Invented facts about the canon are errors that readers of that canon will catch. A detail taken from another adaptation (a game, a film) counts as outside the source unless the story is set in that adaptation.
- **Fix:** check it against the source. If the source doesn't say it, cut it, recast it as a character's belief ("The sergeant guessed it would surface where it went down"), or keep it and list it as invented. When you write fan fiction yourself, end with a short note on which parts are invented.
- **Example:** in an SCP story, "106 drops its prey where it likes, but it has a habit of coming back to where it started" was stated as canon. Neither the SCP-106 file nor the experiment log says so.
- **Retold documents:** when the story retells a document from the canon (a log entry, a note, an interview), compare its quantities, hedges, and attributions with the original. In the same story, the log's "could have resulted in hundreds of causalities" (its typo for casualties) became "the dead would have been counted in the hundreds": a hedge turned into a fact, and casualties into deaths.
- **Why:** the draft-mode rule (facts only from the source) never fires in fiction, because everything in a story is made up. This trigger separates the made-up events from claims about the world they happen in.

## Severity in detect mode

A canon claim the source contradicts, or a rule of the world it doesn't contain, is P1: readers of that canon will catch it, and it changes what the story says about its world. A detail from another adaptation, a retold document that shifts a hedge or a number, and the four craft tells above are P2. Rules this file relaxes keep the catalog's tiers where they still apply. Why: without tiers here, an agent has to rank fiction findings its own way.

*Scope fence:* these checks find what a story's wording gets wrong. Whether the plot works, a character convinces, or the pacing holds is the author's call; flag those only when the user asks for a critique.
