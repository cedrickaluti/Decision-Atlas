# Cedric's Decision Atlas

A field guide to deciding well — an interactive, single-page tool that matches **23 decision-making frameworks** to the decision in front of you, explains each one in plain terms, and turns the most useful ones into calculators you can actually use.

**Live site:** https://cedrickaluti.github.io/Decision-Atlas/

---

## What it does

There's no single "best" decision framework — only a best fit for the situation. The Atlas is built around the two factors that determine fit most: how **reversible** a decision is, and how **knowable** the situation is. It has three modes:

- **Match** — answer up to four quick questions and a map plots frameworks by reversibility and uncertainty, lighting up the right region and ranking your best-fit options with a one-line reason for each. Ties break toward the most purpose-built framework rather than the most generic.
- **Library** — browse all 23 frameworks, filter by domain or trait, or search. Each opens a panel with how to run it, a worked example, and what to watch out for.
- **Tools** — four working templates: a weighted decision matrix, a RICE calculator, an Eisenhower sorter, and a pre-mortem worksheet, each with a copy-to-clipboard button.

## The frameworks

**Comparing & scoring options** — Weighted Decision Matrix · Cost-Benefit Analysis · Expected Value / Decision Trees · Pros & Cons (Franklin's moral algebra)

**Prioritizing & sequencing** — RICE · ICE · MoSCoW · Kano Model · Weighted Shortest Job First · Eisenhower Matrix

**Diagnosing the situation** — Cynefin · One-Way vs Two-Way Doors · OODA Loop

**Deciding as a group** — DACI · RAPID · Six Thinking Hats

**Big personal & values calls** — Regret Minimization · 10/10/10 · Satisficing vs Maximizing · WRAP

**Stress-testing & avoiding mistakes** — Pre-mortem · Inversion · Second-Order Thinking

## Running it

It's a single self-contained HTML file — no build step, no dependencies to install.

- **Online:** open the live URL above.
- **Locally:** download `index.html` and open it in any browser. That's it.

## Hosting it yourself (GitHub Pages)

1. Create a public repository and upload `index.html` to its root.
2. Go to **Settings → Pages**, set **Source** to *Deploy from a branch*, choose the `main` branch and the `/ (root)` folder, and save.
3. Wait a minute, refresh, and the page shows your live URL.

To update later, upload a new `index.html` over the old one — it redeploys automatically.

## Notes

- **No tracking, no backend.** Nothing you type is stored or sent anywhere; everything runs in your browser. The only external resource loaded is Google Fonts.
- **Not advice.** The Atlas is a thinking aid, not financial, legal, or medical advice. The call is always yours.
- **Credit where due.** These frameworks are the work of many thinkers across decades; this tool only summarizes and organizes their ideas. Full attributions are below, and each framework's originator is also shown on its card in the app.

## Credits & attributions

The Atlas stands entirely on the work of the people and groups who created these frameworks:

- **Weighted Decision Matrix (Pugh matrix)** — Stuart Pugh
- **Cynefin** — Dave Snowden
- **OODA Loop** — John Boyd
- **Eisenhower Matrix** — named for Dwight D. Eisenhower; popularized as a time-management matrix by Stephen Covey
- **RICE Scoring** — Sean McBride, at Intercom
- **ICE Scoring** — Sean Ellis
- **MoSCoW** — Dai Clegg
- **Kano Model** — Noriaki Kano
- **Weighted Shortest Job First** — Don Reinertsen; adopted by the Scaled Agile Framework (SAFe)
- **One-Way vs Two-Way Doors (Type 1 / Type 2 decisions)** — Jeff Bezos
- **Regret Minimization Framework** — Jeff Bezos
- **10/10/10 Rule** — Suzy Welch
- **WRAP** — Chip Heath & Dan Heath
- **Pre-mortem** — Gary Klein
- **Six Thinking Hats** — Edward de Bono
- **DACI** — developed at Intuit
- **RAPID** — Bain & Company
- **Cost-Benefit Analysis** — rooted in 19th-century welfare economics, with the early concept credited to Jules Dupuit
- **Expected Value / Decision Trees** — expected value traces to Blaise Pascal and Pierre de Fermat; decision-tree analysis to the field of decision theory (e.g., Howard Raiffa)
- **Inversion** — the maxim "invert, always invert" comes from mathematician Carl Gustav Jacob Jacobi; popularized as a mental model by Charlie Munger
- **Second-Order Thinking** — a systems-thinking idea, widely popularized in decision-making by investor Howard Marks
- **Satisficing vs Maximizing** — Herbert A. Simon
- **Pros & Cons (Moral Algebra)** — Benjamin Franklin

## License

Personal project — use, adapt, and share it however you like. If you'd like a formal license, drop an MIT `LICENSE` file in the repo.
