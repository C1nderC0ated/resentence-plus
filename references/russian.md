# Russian-language writing

Apply this file whenever the text is in Russian or mixes Russian and English, including your own replies and drafts, not only text you edit. Model-written Russian fails in a few recognizable ways: words that look derivable but nobody says, needless loanwords, English idioms and false friends translated literally, bureaucratic officialese, and English punctuation habits. A native speaker reads these as machine Russian, and some of them change the meaning. This file takes precedence over the English catalog in `references/patterns.md` and over English punctuation habits wherever they conflict.

**Why the checks are keyed to visible shapes.** These failures show up in nearly all model-written Russian, and they don't feel wrong from the inside: a coined word looks as plausible to you as a real one. So the triggers below are shapes you can see on the page (a suffix, a verb, a construction), not a sense that something "sounds off." When a shape fires, run its check.

### Quick routing

| You are about to write… | Check | Usual fix |
|---|---|---|
| A noun or verb you built from a root plus a suffix (-ость, -ние, -ация, -ируемость, -ировать), or one you can't recall seeing in ordinary prose | Would a native speaker say it out loud in this register? If you can't confirm it, assume not | A phrase built on a common verb: «проверенность» → «это проверено» |
| A verb made from an English root («коммитаю», «зарелизить») | Is it established slang, correctly conjugated, that this author already uses in this register? | The Russian verb or a standard phrase: «делаю коммит», «выпустить» |
| A Latin- or English-derived word where an everyday Russian word exists («флуктуирует», «имплементировать») | Is this specialist writing for specialists? | The everyday word: «колеблется», «реализовать» |
| A word that resembles an English one («актуальный», «экспертиза», «декада») | Does it mean the same thing in Russian? Often it doesn't | The real equivalent (see False friends) |
| A common word you mean in a rare, folk or dated sense («перекинуться» for a shapeshift) | Will most readers hear its everyday sense first? «Перекинуться» reads as «перекинуться парой слов», "flip over", "defect" or colloquial "die" | The word whose main sense is the one you mean: «обратиться» |
| A set phrase from a trade or setting («задраить люки») | Is the scene in that setting? Nobody seals hatches against the sea on a wreck that no longer floats | The plain words for what is happening: «забаррикадировать входы». See Context fit in `SKILL.md` |
| «является», «осуществлять», «данный», «в рамках», «производить» plus a verbal noun | Is this an official document? | A plain verb or «это»: «производит оплату» → «платит» |
| «Важно отметить», «Стоит подчеркнуть», «Давайте разберёмся» | Does the sentence lose anything without it? | Delete the frame and state the point |
| A dash | Is it grammatically required here? | Required: keep it as an em dash with spaces. Optional: a comma, colon, or new sentence |

When you aren't sure a word exists or sounds natural, use the plain phrase; it is never wrong. If the word comes from the user's own text and they are a native speaker, keep theirs and flag your doubt instead of replacing it. In text you wrote yourself, a translation included, replace a word you doubt instead of flagging it: a flag hands the fix to the reader.

### Rare and coined words

Russian lets you attach -ость, -ние, -ация or -ировать to almost any root, and the result often looks like an everyday word without being one. Models produce these by analogy with English abstract nouns (-ness, -ability) or by deriving a noun from a participle. The test is usage in this register, not grammar: a word belongs when people use it in this kind of text, not when it can be formed or turns up in a dictionary.

- **Rare or coined abstract nouns.** «проверенность» (for "verifiedness"; it is in dictionaries and in the set phrase «проверенность временем», but reads oddly anywhere else), «отлаживаемость» (for "debuggability"; it turns up in software-engineering texts, not in ordinary prose), «понимаемость» (for "understandability"; the word is «понятность»). Recast with a verb or a common noun: «это проверено», «данные прошли проверку», «проверка»; «удобно отлаживать», «удобство отладки»; «понятность», «насколько это понятно». Identify the actual meaning first; these are not one-to-one swaps.
- **Established terms that look coined.** Some -ость words are standard in their field: «воспроизводимость», «масштабируемость», «читаемость», «тестируемость», «сопровождаемость», «обоснованность». Keep them where the field uses them. In casual prose a phrase is often still friendlier («можно повторить», «легко читается»).
- **Specialist words count as unfamiliar.** A real word that only editors, linguists, or physicists use («канцелярит», «флуктуация», «эксплицитный») is, for most readers, as opaque as a coined one. When the reader isn't a specialist, describe the thing in common words instead of naming it with the term.
- **Rare senses of common words.** A word can be common and still wrong when you mean its rare sense. «Перекинуться» does mean a folk shapeshift («перекинулся волком»), but most readers hear «перекинуться парой слов», "flip over", "defect", or colloquial "die" first, so a wounded shapeshifter who «попыталась перекинуться» reads as trying to die. Write «обратиться». It is also a Slavic folk verb, so it brings the wrong mythology to a creature from another culture (see Context fit in `SKILL.md`).
- **When a coined form can stay.** Keep it only when it is an established term in that field, a deliberate part of the author's voice, quoted material, or team slang the user explicitly asked for. Never keep it for its precision: if you can't say it plainly, you haven't pinned down the meaning yet.

Why: a reader who meets an unfamiliar form stops following the sentence and starts decoding the word. For a native speaker it is also an immediate sign that nobody fluent wrote the text.

### Loanwords and English-based slang

Russian borrows freely, and many loans are standard («файл», «сервер», «интерфейс», «дедлайн»). The problem is a loanword where an everyday Russian word says the same thing, and new verbs made by putting a Russian ending on an English root.

- **Learned loans in ordinary prose.** «флуктуирует» → «колеблется», «плавает», «немного меняется»; «имплементировать» → «реализовать», «сделать»; «верифицировать», «валидировать» → «проверить»; «акцентировать внимание на» → «подчеркнуть», «выделить», «привлечь внимание к»; «коммуницировать» → «общаться», «сообщить»; «инсайт» → «наблюдение», «вывод», «догадка»; «челлендж» → «трудность», «задача»; «кейс» → «случай», «пример». Keep the loan in specialist writing where it is the field's term («флуктуации» in a physics paper).
- **Slang verbs on English roots.** Developer and office chat has an established set: «закоммитить» (present tense «коммичу»), «запушить», «смержить», «зарелизить», «заапрувить», «юзать». They fit only when the author already writes that way in that register. Don't introduce them into prose, don't turn neutral text into slang, and never build a new one or conjugate one by analogy: «коммитаю» is a model's mistake for «коммичу». In prose: «делаю коммит» or «фиксирую изменения», «выпустить», «одобрить», «использовать».
- **Avoid forced purism too.** Don't replace a word the audience uses every day («браузер», «сервер», «API», or «дедлайн» in a team that says it) with an obscure Russian equivalent. That is the same mistake in the other direction.

Why: needless loans make the text sound like translated corporate English, and invented hybrids sound like a parody of developer speech.

### Calques and false friends

A calque copies an English construction word for word. Every word is Russian; the sentence isn't.

**False friends** (the Russian word exists but means something else):

| English meaning | Wrong | Right |
|---|---|---|
| actual, real | актуальный (means current, relevant) | настоящий, фактический, реальный |
| accurate | аккуратный (means neat, careful) | точный |
| decade | декада (means ten days) | десятилетие |
| eventually | эвентуально (means possibly) | в итоге, со временем |
| expertise | экспертиза (means an expert examination) | опыт, знания, компетенция |
| dramatically (by a lot) | драматически (means tense, tragic, to do with drama) | резко, сильно |
| sympathetic | симпатичный (means likeable, pretty) | сочувствующий, отзывчивый |
| intelligent | интеллигентный (means cultured, well-mannered) | умный |
| argument (a quarrel) | аргумент (means a point in reasoning) | спор, ссора |
| pretend | претендовать (means to lay claim to) | притворяться, делать вид |

Business Russian has started using «экспертиза» for "expertise"; keep it if the author does, but don't introduce it.

**Calqued constructions:**

- "This allows us to…" → «Это позволяет нам…». Usually say it directly: «Так мы можем…», «Благодаря этому можно…», or lead with the action. Keep «позволяет» when something literally permits or enables something.
- "There are several ways…" → «Существует несколько способов…». Often lighter as «Способов несколько:».
- "on a daily basis" → «на ежедневной основе» → «каждый день».
- "address the problem" → «адресовать проблему» → «заняться проблемой», «решить проблему», «ответить на вопрос».
- "at the end of the day" → «в конце дня» → «в итоге», «в конечном счёте». Keep «в конце дня» only when it means the evening.
- "be on the same page" → «быть на одной странице» → «одинаково понимать», «договориться».
- "That makes sense" as a reply → «Это имеет смысл» → «Понятно», «Логично». «Имеет смысл попробовать» in the sense of "worth trying" is native and stays.
- "provide" → «предоставлять» everywhere → «давать», «показывать», or a specific verb.
- "the" turned into «данный» or «этот». Russian has no articles; drop the demonstrative unless it actually points at something.
- Possessives translated every time: «Он положил свою руку в свой карман» → «Он сунул руку в карман». Russian leaves out possessives the context already makes clear.
- Generic "you" in instructions: "If you click X" → «Если вы нажмёте X» is correct but heavy in documentation; «Если нажать X» or the imperative «Нажмите X» reads more naturally.
- "being" and -ing chains → «будучи», «являясь», strings of деепричастия. Split into two clauses with ordinary verbs.

Why: each calque is grammatical, which is why it survives proofreading, and together they make the text read like a translation.

### Officialese (казённый язык)

The language of official paperwork leaks into ordinary Russian prose, and models reproduce it heavily because so much formal text is written this way. Most people call it «казённый язык» or «канцелярский язык» («канцелярщина» usually means the red tape itself). Editors call it «канцелярит», a term Корней Чуковский coined in *Живой как жизнь* (1962); Нора Галь's *Слово живое и мёртвое* is the classic editor's guide to it. Most readers don't know the editors' term, so in text for a general audience, describe the problem instead of naming it.

Its signs:

- **A verb split into a verb plus a noun.** «производить оплату» → «платить»; «осуществлять контроль» → «контролировать», «следить»; «проводить проверку» → «проверять»; «оказывать помощь» → «помогать». Fixed terms stay: «оказать первую помощь», «принять решение».
- **Chains of genitives.** «обеспечение повышения качества обслуживания клиентов» → «чтобы клиентов обслуживали лучше». Two nouns in a row in the genitive are common; three or more are the sign.
- **Stock official words.** «является» (→ «это», a dash, or nothing), «данный» (→ «этот»), «осуществлять» (→ «делать» or the specific verb), «имеет место» (→ «есть», «бывает»), «в рамках» (→ «в», «во время», «для»), «в целях», «с целью» (→ «чтобы»), «в связи с тем, что» (→ «потому что», «так как»), «в случае если» (→ «если»), «на сегодняшний день», «в настоящее время» (→ «сейчас»), «по причине» (→ «из-за»), «при наличии», «при отсутствии» (→ «если есть», «если нет»), «вышеуказанный» (→ «этот», «упомянутый»).
- **Passives that hide the actor.** «Было принято решение» → «Мы решили», when the source says who decided; don't invent the actor. «Проверка осуществляется системой» → «Система проверяет».

Keep the official register where it belongs: contracts, official letters, legal text, and quotations. Don't "fix" a document the user needs in that register.

Why: each sign adds words without adding meaning, and the reader has to unpack the nouns to find out who does what.

### Model Russian: stock phrases

These are the Russian counterparts of the English chatbot tells. Apply the same severity and pass conditions as the English equivalents.

- **Framing openers:** «Важно отметить, что», «Стоит отметить», «Стоит подчеркнуть», «Следует учитывать, что», «Важно понимать, что», «Нельзя не отметить». Delete the frame; the fact is still there.
- **Chatbot openers and closers:** «Давайте разберёмся», «Давайте рассмотрим», «Погрузимся в…», «Надеюсь, это поможет!», «Отличный вопрос!», «Конечно! Вот…». Remove them.
- **Era openers:** «В современном мире», «В наше время», «В эпоху цифровых технологий», «В условиях стремительно меняющегося мира». Cut, or state the specific context the source gives.
- **Inflated significance:** «играет ключевую роль», «является неотъемлемой частью», «открывает новые возможности», «выводит на новый уровень», «настоящий прорыв», «мощный инструмент», «уникальный», «инновационный», «комплексный подход», «широкий спектр». Say what the thing does, using what the source supplies.
- **Vague quantifiers:** «ряд» and «целый ряд» («ряд преимуществ»), «различные», «многочисленные». Name the items or give the number when the source has them.
- **Summary signposts:** «Таким образом», «В заключение», «Подводя итог», and «В целом» as an opener. Cut them and let the last real point close the text.
- **Contrast frame:** «Это не просто X, а Y», «Речь идёт не о X, а о Y». Same rule as the English contrast negation: keep it only when someone actually claimed X.
- **Filler adverbs:** «по сути», «фактически», «действительно», «буквально» when they add emphasis instead of meaning.
- **«ключевой» as a reflex adjective** («ключевые аспекты», «ключевые моменты»), the counterpart of English "key." Use it once, for the point that really is central.

Why: a Russian reader recognizes these first as machine text, and they carry no information.

### Syntax and word order

- **Put the verb back.** «Система проверяет данные», not «Осуществляется проверка данных системой». A clear verb almost always beats an abstract noun.
- **New information goes last.** Russian word order follows what is already known versus what is new: «В комнату вошёл человек» (someone new came in) is not the same as «Человек вошёл в комнату» (the person we already know). Copying English subject-verb-object order everywhere puts the emphasis in the wrong place. Keep the source's emphasis; don't add your own.
- **Fewer pronouns.** Russian drops a subject the context makes clear more often than English, especially in conversation and in a run of sentences about the same subject: «Я думаю, что я смогу» → «Думаю, смогу».
- **Break up «который» chains.** Two «который» clauses in one sentence are the limit; split the rest into separate sentences.
- **Don't let the English original dictate the Russian sentence.** When editing translated text, don't preserve an awkward construction just because it mirrors the source language.

### Punctuation

Russian punctuation is mostly grammatical rather than stylistic, so the English punctuation habits in the main catalog don't carry over.

**Dashes.** Russian needs a тире in several grammatical positions. Use a real em dash there, with spaces, and nowhere else: a dash for a pause, an aside, or emphasis follows the English rule and goes. Don't overdo the required ones either. They rarely cluster in natural text, so if a paragraph has more than two, or two sentences in a row each have one, check every dash against the list below and rebuild some of those sentences around an ordinary verb, even where the dash would be correct. Decide like this:

1. **The dash is required.** Use an em dash with spaces:
   - between subject and predicate with no linking verb when both are nouns, infinitives, or numerals, in any combination: «Москва — столица России», «Наша задача — успеть к пятнице», «Дважды два — четыре»; and before «это», «вот», «значит» in that position: «Главное — это сроки»;
   - after a list, before the word that sums it up: «Книги, журналы, газеты — всё лежало на полу»;
   - where a verb is left out and the gap is felt: «Я — в магазин, он — домой»;
   - between two clauses without a conjunction when the second is a consequence, a contrast, or a sudden turn: «Пришёл — всё изменилось»;
   - in dialogue, at the start of each line and between the speech and the author's words: «— Привет, — сказал он.»
2. **No dash, even where it looks like the first case:** when the subject is a pronoun («Я программист», not «Я — программист», unless you deliberately stress it), when the predicate has «не» («Это не баг»), and after «тоже», «также», «ведь», or a comparison with «как» («Он тоже врач»).
3. **The dash is optional or stylistic** (a pause for effect, an aside). Use a comma, a colon, parentheses, or a new sentence instead.
4. **Never dodge a required dash with «является».** That trades a punctuation rule for officialese. Keep the dash, or rebuild the sentence around an ordinary verb.

**Commas.**

- Russian requires commas before subordinate clauses («что», «чтобы», «который», «если», «когда», «потому что»), around a participial phrase that follows its noun, around a деепричастный оборот, and before «а» and «но». Don't drop them out of English habit.
- English puts a comma after an introductory phrase; in Russian a plain opening adverbial of time or place takes none: «В 2020 году мы переехали», not «В 2020 году, мы переехали». Parenthetical words and phrases do take commas («конечно», «например», «во-первых», «по-моему», «по словам автора»), and so does a leading деепричастный оборот.

**Other conventions.** Use these in new text; in someone else's text, keep their choices.

- Quotation marks are «ёлочки», with „лапки“ for a quote inside a quote. Straight quotes stay in code and in plain-text destinations that need them.
- Headings use sentence case. Months, days of the week, languages, and nationalities are lowercase: «в среду», «в октябре», «на русском».
- Numbers in prose take a decimal comma (3,5). Four-digit numbers stay solid (5000); from five digits, group thousands with a non-breaking space (10 000). Code and data keep their own format.
- Ranges take an unspaced en dash: «2010–2020», «5–7 дней».
- «ё»: follow the source. In new text, write ё at least where leaving it out changes or blurs the meaning («всё» and «все», «узнаём» and «узнаем»).

### Register and address

- Match the source's «ты» or «вы» and keep it consistent. In chat, don't switch to «вы» because the topic became serious.
- Capitalized «Вы» is a convention for addressing one person politely in a letter or a formal personal message. Don't use it in chat, in documentation, or when addressing several people.
- Casual Russian chat has its own typed register (lowercase starts, «)» as a smile, clipped phrasing). Keep it when the author writes that way; never fake it.

### Bilingual terms and mixed technical text

- **Keep bilingual terms semantically equivalent.** If both an English term and a Russian equivalent appear, they must refer to the same concept, not merely a related one. For example, `UI` means «пользовательский интерфейс»; it does not automatically mean «графическая оболочка», which is narrower and describes a different thing. Check the intended concept before pairing or swapping terms. Don't alternate between near-synonyms for variety. If a distinction matters, preserve it and explain it rather than blurring it.
- **Keep identifiers exact.** In mixed-language technical writing, preserve exact identifiers and quoted UI labels. Keep each term consistent across the text, and translate only user-facing prose, not code, command names, filenames, or literal interface labels that must remain exact.
- **Keep product names in their own script.** Write «GitHub», not «Гитхаб», in anything formal; casual chat may follow the author's habit.

### Don't apply the English catalog literally

A phrase, repetition, dash, or sentence shape that looks suspicious under an English-oriented rule may be ordinary Russian. Judge it by Russian grammar, register, genre, and the surrounding text. Likewise, don't preserve an awkward Russian calque merely because the English original uses a common phrase.

### Worked example

> **Before:** «Важно отметить, что данный подход является ключевым для обеспечения проверенности данных — он позволяет осуществлять их контроль на ежедневной основе.»
>
> **After:** «Этот подход — основа проверки данных: благодаря ему можно каждый день следить за данными.»

What changed: the frame «Важно отметить, что» is gone; «данный» became «этот»; «является ключевым» became a required dash between two nouns; the coined «проверенность» and the genitive chain «обеспечения проверенности» became «проверки»; the em dash became a colon; «позволяет осуществлять их контроль на ежедневной основе» became «благодаря ему можно каждый день следить за данными».

*Scope fence:* this example teaches surface fixes. Whether «основа» is as strong as the author's «ключевой», and whether «следить» covers what they meant by «контроль», are meaning checks you still run against the source, and ask about when they matter.

### Final pass for Russian text

Before delivering Russian text, reread it once looking only for these shapes, in this order: a word you built or aren't sure of; a common word you mean in a rare sense, or a set phrase from a setting the scene isn't in; an English root with a Russian ending; a false friend from the table; «является», «осуществлять», «данный», «в рамках», and verb-plus-noun splits; a framing opener or summary signpost; every dash, checked against the dash rules. Send each hit through its section above. This reread is a check, not an editing pass under the iteration budget.

Severity in detect mode: coined words, false friends, rare senses, and context misfits are P1, and fix them first because they can change the meaning; model-Russian stock phrases are P1, like their English counterparts; officialese, calques, and punctuation habits are P2.
