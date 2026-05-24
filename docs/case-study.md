# Case study — AI Assistant Dashboard UI

## Context

I designed this as a portfolio piece: a small mobile app for talking to an AI assistant. The goal was to cover a realistic flow end to end—not just one pretty home screen.

## The problem I was solving

Most chat apps either throw you into an empty thread or overwhelm you with options. I tried to balance:

- A friendly first screen so new users are not staring at a blank chat
- A familiar message UI once they are in
- A separate place to browse ideas (Explore)
- Settings that feel personal without hiding important AI options
- Voice as its own mode, not a tiny icon lost in the composer

## The five screens

1. **Welcome** — Greeting, four suggested prompts, one clear CTA.
2. **Main chat** — Sidebar history, assistant intro message, user bubble example, input + send.
3. **Explore** — Filter chips and recommendation cards with short descriptions and tags.
4. **Settings** — Avatar, dark mode / notifications toggles, response length, model, language.
5. **Voice** — “Listening…” state, rings + waveform, example utterance, Cancel / Done.

## Decisions I made along the way

| Choice | Why |
|--------|-----|
| Dark UI | Fits the product type and keeps focus on content |
| Purple → blue gradients | Marks primary actions without adding extra chrome |
| Prompt cards on Explore | Easier to scan than a long list of plain text |
| History in the chat view | Quick jump between topics without a separate “archive” screen |
| Dedicated voice screen | Room for feedback (waveform, status copy) while recording |

## Figma setup

- **Wireframes** — layout and hierarchy before polish
- **Final UI** — color, type, and components
- **Prototype** — links between screens for demos and interviews

## Links

- [Design file](https://www.figma.com/design/o9THnW4EMHsg19KGhIdKWK/AI-Assistant-Dashboard-UI?node-id=1-2)
- [Prototype](https://www.figma.com/proto/o9THnW4EMHsg19KGhIdKWK/AI-Assistant-Dashboard-UI?node-id=1-2)

Screenshots live in [`../screenshots/`](../screenshots/).
