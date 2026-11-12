# Decision Rights over Personal Information in the Age of Personal AI

**Self-Determination of Personal Information × Personal Context × Bot Accounts**

*A sequel to the bot account studies — what it takes for a bot that has long remembered me to follow what I want today.*

- Author: **Ha Woo Sung (Ryo Ha)** — sopia19910@gmail.com
- Date: November 12, 2026
- Essays in this repository:
  - 📄 [English — Decision Rights over Personal Information in the Age of Personal AI](%5BEN%5D%20Decision-Rights-over-Personal-Information.pdf)
  - 📄 [한국어 — 개인 AI 시대의 개인정보 의사결정권](%5BKR%5D%20Decision-Rights-over-Personal-Information.pdf)

---

> **Does my bot have to say why I can't meet at three in the afternoon?**

At three tomorrow I am taking my father to a hospital appointment. My bot, asked by someone else's bot for a meeting, needs that note to work out that I am free from half past four — but the reply should say only *"Tomorrow works from half past four."* I want an assistant that can hold on to what it remembers and still be sparing with what it says.

When the judgment is handed to a bot, reading the calendar, weighing the circumstances, and writing the reply can happen in three different places — my device, an external model, and two bots exchanging messages. The final sentence alone does not show how far my circumstances traveled.

## What "Decision Rights over Personal Information" Means

The essay defines them as the right to:

| Act | Meaning | Where it is covered |
|---|---|---|
| **Decide** | who may use information about me, for what purpose, and how far | Part I, Chapters 4–5 |
| **Check** | how that information was actually used | Chapter 6 |
| **Change** | the terms of its future use | Part III |

The legal starting point is the **right to self-determination of personal information** recognized by the Constitutional Court of Korea (2005) and the rights set out in the Personal Information Protection Act. "Decision rights over personal information" is not a separate statutory right; it is the name this essay gives to that purpose as applied to the **memory, judgment, and outbound communication of personal AI**. Throughout, the rights guaranteed by law and the product design the essay proposes are kept distinct.

## Two Scenes

The argument is followed through two concrete scenes:

- **Coordinating a meeting time** — two bots agree on "five o'clock, thirty minutes, manuscript review" while the reason three o'clock does not work stays in my calendar.
- **Inquiring at a hotel** — my bot knows about my father's knee and my budget of 180,000 won a night, but the hotel only needs the dates, the number of guests, and whether there is a step-free route to the room.

## Key Distinctions

**A fact, an inference, and an instruction are different records.** "I can't meet at three this Tuesday" is a fact I stated; "wants to keep Tuesday afternoons free" is the bot's inference; "decline Tuesday afternoon requests from now on" is an instruction only I can give. A single line labeled "user preference" can hide three different authors.

**A memory should carry its conditions of application.** "On trips accompanying Father, asked to check for a step-free route" — not just "dislikes stairs" — so the condition does not follow me onto a solo business trip. **Retention and use are decided separately**: a record can be kept without being used for future recommendations.

**Information can belong to more than one person.** My father's hospital schedule is his affair as well as mine; unpublished manuscripts in an editor's notes remain the publisher's. Being "in control" means handling what came mixed into one chat window along the boundaries of people and work.

**Common context holds only what both sides need** — purpose, candidate time, duration, status — not each side's private reasons.

**Delegation has a scope.** "Look into places to stay" is not "book and prepay." Within a delegated scope (recipient, items, purpose, period) the bot does not ask again; when the scope changes — passing the inquiry to a travel agency, disclosing the budget, booking — it asks again.

**Checking means tracing the sentence that actually went out** — what I asked for, the scope I approved, the items actually sent and to whom, and what came back.

**Correcting and withdrawing must reach the bot's next action.** A correction succeeds only if the next task stops reading the old summary. Withdrawal can span several organizations: stopping my own bot is not the same as canceling alerts registered with hotels.

**Moving to another AI:** take along confirmed preferences, leave ended permissions in their ended state, and carry pending requests as task status — not as a fresh instruction to act again.

## Grounded in Evidence — and Its Limits

The essay reviews **25 Korean and 40 overseas and international sources** (court decisions, statutes, regulators' materials, academic research, technical standards, and product documentation) and states how far each kind of evidence reaches:

| Type of evidence | What it tells us | What it does not tell us |
|---|---|---|
| Statutes and decisions | who can demand what | whether a bot actually behaves that way |
| Regulators' materials and field surveys | issues and risks raised in practice | settled rules or measured error rates |
| Model experiments and user studies | what a model sent under specific conditions | figures that generalize to every service |
| Technical standards and product documentation | how to express authority and records | whether the recipient processed data as agreed |

It also discusses memory-evaluation studies (Memora, CIMemories, OP-Bench), the Lee Luda and Meta sanctions by Korea's PIPC, the CJEU's ruling on identifying actual recipients, California's authorized agents and Global Privacy Control, India's consent managers, and the EU Data Governance Act.

## Contents

| Part | Chapters |
|---|---|
| Introduction | Does my bot have to say why I can't meet at three in the afternoon? |
| **I. Information a Person and a Bot Build Together** | how what I said becomes a judgment about me · how far I can decide about information built up in my bot · what to remember and use again |
| **II. When My Bot Works with Other Bots** | what becomes common context · what authority goes with a delegated task · what was sent to whom in my name |
| **III. After I Change My Mind** | correcting a memory or withdrawing permission · which decisions carry over to another AI |
| **IV. As Far as the Evidence Reaches** | can a bot exercise my rights on my behalf? · how to check whether this design works |
| Conclusion | For a bot that has long remembered me to follow what I want today |

## Companion Works

This essay is a sequel to two earlier works by the same author, cited in its references:

- 📘 [**Bot Accounts** — In Whose Name Does an AI Act?](https://github.com/sopia19910/Bot-Accounts) — linking the bot that carried out a task, the person who delegated it, and the authority it exercised
- 📘 [**The Future Structure of Bot Accounts** — Bot ID × Context Password × MyData](https://github.com/sopia19910/Bot-account-future-architecture) — holding the context built up with a bot and carrying the relationship into other AI environments

## License

Released under the [MIT License](LICENSE).

---

*For a single schedule entry I made three decisions: what my bot may refer to, what to share with the other party, and what the bot may do in my name. Decision rights over personal information are what make those decisions carry through to the bot's next action.*
