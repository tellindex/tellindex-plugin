# Answering about a perfume

## Reading `fragrance_profile`

| Part | What it is |
|---|---|
| `tell.score`, `tell.zone` | the Tell and its zone — said together; `zone_meaning` is the zone's definition |
| `tell.verdict` | the Tell line: the perfume's one-liner, written per language |
| `tell.labels[]`, `tell.other_labels[]` | the 0–3 reaction labels on the perfume's card (they explain the number), then the others that fired; definitions in `meaning` |
| `axes[]` | Heard, Divisive, Recognized, Compared, Fits — score vs other perfumes, plus Tell Index's `reading` of this perfume on each |
| `smell` | `summary` (a few words), `description` (a short portrait), `unfolding` (opening → drydown), `noticed_first` and `background` notes, `accords` with strength words |
| `wear` | longevity and sillage ranges, projection word, `seasons` and `day`/`night` fit, tags `best`, `role`, `safe`, `careful` |
| `scenes` | `worn_for`: where people actually wear it (shares); `notes`: how it plays in an office, on a date, in a club, in heat — each with a dosing `tip` |
| `people` | `feeling` (love / like / mixed / dislike, shares); `reactions` and `character` (vs other perfumes, 50 = typical); `crowd_says` (what people keep saying, shares; `complaint` marks complaints); `debates` (what people argue about, both sides, Tell Index's take) |
| `voices[]` | five witnesses — a colleague, a date, an enthusiast, a bartender, the older generation — each with one line |
| `history[]` | its story from launch to today |
| `counterfeit` | risk 1–4 with its words, why, practical checks |

**How the numbers become an answer.** Two kinds of 0–100 live here: shares of people
(`feeling`, `crowd_says`, `debates`, `worn_for`) and comparisons with other perfumes
(`reactions`, `character`, axes). Read each kind its way, then turn it into what people around
the wearer do, where, and what that means for this person's plan. Season scores are relative
within the perfume — read where it peaks; day and night split 100 between them.

**When the data disagrees with itself.** Labels describe what stands out in reactions; a label
next to an opposite-looking score means reactions run strong both ways or that one trait
stands out — say the honest version briefly. The Tell number and zone outrank written texts.

**When something is missing.** `pending` → call again after ~5 seconds, up to twice. A text in
another language is still being written in theirs: same. A part that is absent and not pending
doesn't exist for this perfume — answer from the rest. A perfume `fragrance_search` doesn't
find: say Tell Index doesn't have it yet, answer from general knowledge as yours, or offer the
close match the search found.

## Playbooks

Lead with what's asked; use what serves it; pick the page reason from
`tellindex-pages.md` that fits this question. A question with two parts: lead with the part
that's really asked.

- **What does it smell like?** The scent in your words from `summary` and `description`, how it
  unfolds, the notes people notice first. The Tell line when it captures the character.
- **Is it loud? Will people notice?** Tell and zone as who notices and from how far: presence
  labels (beast mode, skin scent, nose-blind), the Heard reading, sillage, longevity. Dosing from
  the scene tips: how many sprays, where, when.
- **Can I wear it to X / in season Y?** Yes, yes with a light hand, or better not — and why: the
  matching scene line and tip, `safe` / `careful`, where it peaks across seasons and day/night,
  where people actually wear it.
- **Compliments, what people think.** The mechanism: who reacts and at what distance (presence
  labels, sillage), how it stands out in compliments and questions, whether people agree on it or
  split and over what, the usual complaint. A witness whose setting matches theirs (a date, an
  office) makes it vivid.
- **Why is everyone obsessed / is the hype real?** What actually drives the buzz: how widely it's
  recognized, its story to today (`history`), what people love, what they argue about, whether
  it smells expensive or familiar.
- **Is it worth it?** Your verdict for this person: what people love against what they argue
  about, how it comes across (expensive, familiar), the main complaint; prices in their market.
- **Blind buy?** The risk for them: a divisive axis, labels such as acquired taste, love it or
  hate it, sharp, or a split `feeling` all point to trying first. Samples and decants from
  `fragrance_prices`; how often it's faked when the risk is 3–4.
- **A or B?** Both profiles. The pick for their situation first; a small side-by-side when it
  helps: Tell · zone and the Tell line of each, the smell in a few words, where each shines, the
  deciding difference.
- **How long does it last?** Longevity, what people say about it, nose-blind if labeled, a dosing
  tip.
- **Is it faked? Is my bottle real?** The risk in words, why, the high-priority checks as a quick
  how-to.
- **Does it have note X?** Perceived notes and accords — whether people actually notice it.
- **Allergens, layering, celebrities** live on the page and in Worlds.
- **Gifts, dupes, cheaper, similar, what next** → `alternatives.md`.
