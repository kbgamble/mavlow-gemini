# Mavlow for Gemini

Mavlow lets you move social content from Gemini into your Mavlow workflow for review, scheduling, and publishing. Create captions in Gemini (or paste your own), then say **Send to Mavlow** — the draft lands in your Queue. You stay in control of approval and publish.

## Installation

Requires [Gemini CLI](https://geminicli.com/docs/get-started/installation/).

```bash
gemini extensions install https://github.com/kbgamble/mavlow-gemini
```

Then start Gemini CLI (`gemini`) and confirm the extension is listed:

```text
/extensions list
```

## Authentication

The first time you use a Mavlow tool, Gemini opens your browser so you can sign in to Mavlow, choose your default workspace, and approve the connection. No API keys are stored in this extension.

You can also start auth explicitly:

```text
/mcp auth mavlow
```

Revoke anytime in Mavlow → **Integrations → Connected AI**.

## Example usage

- "What can I do with Mavlow?"
- "Use my Mavlow brand and write an Instagram caption about our fall sale, then send it to Mavlow."
- "Send this to Mavlow: We're open late Fridays through September — stop by after work."
- "Save this LinkedIn post to Mavlow."
- "What's on our Mavlow content calendar this week?"
- "List my Mavlow drafts."

## What Gemini can do via Mavlow

When connected, Gemini can:

- Read your brand voice, facts, and preferences
- See connected social channels
- Read recent posts, drafts, and calendar
- Create and update social drafts in your Queue

Gemini **cannot** publish, schedule, attach media, connect social accounts, or change billing. Open the returned Queue link in Mavlow to attach media, approve, schedule, and publish.

## Requirements

- [Gemini CLI](https://geminicli.com/) (stable)
- A [Mavlow](https://mavlow.com) account ([Start free](https://mavlow.com/start))

## Links

- Product: [https://mavlow.com](https://mavlow.com)
- How Send to Mavlow works: [https://mavlow.com/send-to-mavlow](https://mavlow.com/send-to-mavlow)
- Privacy: [https://mavlow.com/privacy](https://mavlow.com/privacy)
- Terms: [https://mavlow.com/terms](https://mavlow.com/terms)
- Support: [hello@mavlow.com](mailto:hello@mavlow.com)

## License

MIT
