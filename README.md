# Disclosure Trainer for Interpreters

**[Open the trainer →](https://axiya3749.github.io/disclosure-trainer/)**

Banks and insurers open every call with a long scripted disclosure, read fast.
Interpreters can't use any tools mid-call, so the only way through is to know
these passages cold before the phone rings.

This drills them the way the job actually works.

---

## How it works

Four steps, in the order the real task happens:

1. **Listen.** You hear the English. No text on screen, because on a call there
   isn't any. Adjustable playback speed lets you practise slower than real, then
   faster than real.
2. **Take notes.** A notepad for your own symbols and shorthand. Notes are saved
   per passage, so you can see how your note-taking changes over time.
3. **Interpret and record.** Work from your notes, speak the Chinese out loud,
   record it.
4. **Check.** Reveal the source to find what your notes missed. Reveal the
   reference rendering to check your accuracy. Play your recording back against
   both.

Then rate yourself: **Hard** brings it back tomorrow, **OK** in a few days,
**Easy** in a week or more. Anything you mark as mastered leaves the rotation
entirely. However many passages you add, you only ever face the ones due today.

## Other things it does

- Simplified and Traditional Chinese, switchable
- Split long passages sentence by sentence
- Numbers and percentages highlighted, since that's where interpreting fails most
- Shuffle, so you learn the passages and not the order
- Print a bilingual sheet
- Import and export as JSON; import merges and never overwrites your own edits
- Interface in English or Chinese
- Dark mode, and animations respect `prefers-reduced-motion`

Keyboard: <kbd>R</kbd> play · <kbd>P</kbd> pause · <kbd>C</kbd> next sentence ·
<kbd>B</kbd> play back · <kbd>←</kbd><kbd>→</kbd> move between passages

## Where the passages come from

Only public sources. Nothing from a real call, ever.

| Set | Source |
|---|---|
| Banking, 30 passages | [Regulation Z, Appendix G](https://www.consumerfinance.gov/rules-policy/regulations/1026/g/) federal model forms and clauses |
| Health insurance, 38 passages | [Medicare.gov](https://www.medicare.gov/), [42 CFR 431.210](https://www.ecfr.gov/current/title-42/part-431/section-431.210), [California DHCS](https://www.dhcs.ca.gov/) |

Also useful if you want to add your own: the CFPB's
[credit card agreement database](https://www.consumerfinance.gov/credit-cards/agreements/),
which holds agreements from more than 600 issuers, all public by law.

Load a set with **Import**. It merges with what you already have and fills only
blanks, so your own edits survive.

## Rules for anything you add

**Never enter client private information.** No names, dates of birth, account or
member numbers, addresses, phone numbers, medical details, case details. This
tool holds standard scripted boilerplate and nothing else.

Strip specific brand and product names too. It keeps you clear of copyright on
proprietary wording, and generic phrasing makes the material useful to more
people.

## The Chinese renderings

The bundled Chinese is a starting draft, not an authority. **Review it before you
drill it** — practising a wrong rendering until it's automatic is worse than not
practising at all. Use Edit to replace anything with the wording you actually
say on calls.

## Running it

One HTML file, no build, no dependencies, no server, no accounts, no tracking.
Your passages live in your browser's local storage. Export regularly if you care
about them.

Microphone access requires HTTPS, so recording works on the hosted version but
not when you open the file directly from disk.

## Adapting it for another language

The English source text and the practice logic are language-neutral. Replace the
Chinese field with your own language, adjust the two interface strings at the top
of the file, and it works the same. If you build a version for Spanish, Vietnamese,
Arabic, or anything else, open an issue and I'll link it here.

## License

MIT. Do what you like with it.

---

<sub>Built by a working Mandarin interpreter who needed it. Not affiliated with any
bank, insurer, or government agency.</sub>
