<div align="center">

# Cluence

### Describe it. Don't name it.

**An AI-powered daily English description game.**

[How to Play](docs/game-rules.md) · [Documentation](docs/README.md) · [Roadmap](docs/roadmap.md)

</div>

---

## Make AI guess what you mean

**Cluence** is a daily English-speaking game where you describe an object without saying its name. An AI listens to your description and guesses the object. If it guesses incorrectly, you can add another clue in English.

The challenge is to communicate clearly in as few attempts as possible. After each game, receive feedback on pronunciation, grammar, vocabulary, and clarity.

> **Project status:** Concept and specification phase. The gameplay and scoring described here are proposed rules, not released features.

## How it works

1. **See an object.** Get one assigned object each day. Different players may receive different objects.
2. **Describe it in English.** Speak for up to 30 seconds per attempt without saying the object's name or a direct synonym.
3. **See the AI's guess.** The AI returns **one** object as its guess.
4. **Refine your description.** If the guess is wrong, add another clue. Previous descriptions remain part of the context.
5. **Earn a score.** Succeed within five attempts, then review your English feedback and leaderboard standing.

Read the [complete game rules](docs/game-rules.md).

## Features

- **One challenge a day** — a new opportunity to practice and compete.
- **AI guessing** — explain the object clearly enough for the AI to identify it.
- **Up to five attempts** — each additional clue should improve the AI's understanding.
- **English learning feedback** — review pronunciation, grammar, vocabulary, and descriptive clarity after playing.
- **Competitive scoring** — balance successful communication and English quality.
- **Leaderboards** — compare daily scores, with weekly and monthly rankings planned.

## Scoring

The proposed score is **1,000 points** in total:

| Category | Maximum |
| --- | ---: |
| AI guessing success / number of attempts | 400 |
| Pronunciation | 200 |
| Grammar | 150 |
| Clarity of description | 150 |
| Vocabulary | 100 |
| **Total** | **1,000** |

Scoring calibration, object difficulty, and ranking fairness require testing before competitive release. See [Scoring](docs/scoring.md).

## Documentation

| Document | Description |
| --- | --- |
| [Documentation index](docs/README.md) | Overview of the project documentation |
| [Game overview](docs/game-overview.md) | Concept, audience, and game experience |
| [Game rules](docs/game-rules.md) | Attempts, guesses, forbidden words, and end conditions |
| [Scoring](docs/scoring.md) | Score allocation and fairness considerations |
| [AI system](docs/ai-system.md) | AI guessing, answer matching, and evaluation boundaries |
| [Learning feedback](docs/learning-feedback.md) | Post-game pronunciation and language feedback |
| [Ranking](docs/ranking.md) | Daily, weekly, and monthly leaderboards |
| [Architecture](docs/architecture.md) | Proposed technical structure |
| [Roadmap](docs/roadmap.md) | MVP scope and future development |

## Development

Cluence is currently being designed. The intended first milestone is a playable web prototype covering daily challenges, voice input, AI guessing, basic feedback, and daily rankings.

The architecture is not finalized. See the [architecture proposal](docs/architecture.md) and [roadmap](docs/roadmap.md).
