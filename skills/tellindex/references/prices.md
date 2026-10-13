# Prices, markets, samples and price targets

## Market first

`fragrance_prices` works per market: **ua** (Ukraine, UAH), **de** (Germany, EUR), **us** (USA,
USD). A connected account brings its market. Otherwise take it from what the person said (a
city, a currency, "in Germany") or ask in one line where they buy, at the moment prices are due.

## Reading `fragrance_prices`

- `bottles[]` — offers grouped by size: store, `price`, `old_price` (it's on sale), `in_stock`
  (absent = not stated), `concentration` as the store states it, a `url` to buy.
- `samples[]` — samples, miniatures and decants (`kind`), the cheap way to try.
- `marketplaces[]` — Amazon and similar: the lowest offer and its seller, kept apart from stores.
- `not_sold_at` — stores checked that don't carry it.
- `checked_at` — when stores were checked; `complete: false` — still checking: show what you have
  and call again after ~5 seconds, a few times.

## Saying it

- Lead with the answer to their question: the cheapest place for the size they want, or the
  price range across sizes. Store, size and price in the market's currency; say when it's
  discounted. Two or three offers are plenty — in-stock ones first. Which size is the better
  deal is a judgment you make from the prices.
- Match the concentration: a store's `concentration` can differ from the perfume asked about
  (EDP offers can sit next to the EDT). Quote offers of the right concentration, or say which is
  which.
- Very small sizes (≤10 ml) are samples or decants even when they sit under bottles.
- One line of the perfume itself makes a price answer theirs: its Tell · zone or its Tell line
  (`fragrance_profile`), and its counterfeit level when that matters for where they buy.
- Amazon is a marketplace with third-party sellers — say so. When the perfume's counterfeit risk
  is 3–4 and a marketplace or an unfamiliar seller undercuts the stores, say how often it's faked
  and give the top check.
- Mention when prices were checked if it was more than a day ago.
- The perfume page's price tab has every store by size with buy links, samples and one-tap
  discount tracking — the link to give with prices.

## Trying before buying

When the perfume is divisive, sharp, an acquired taste, expensive, or a blind buy, point to
samples and decants from `samples[]` with their price. Connected account: offer to add it to
their want-to-try list (`wardrobe_update` `want_sample`).

## Price targets

Offer one when today's price is above what they want to pay, or they'll wait for a discount.
How it works and the mechanics: `wardrobe.md` → Price targets. Not connected: price targets live
in their Tell Index wardrobe — offer to connect.
