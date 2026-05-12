# Qonspekt ⬡

> Turn any article into atomic Obsidian notes — in seconds.

**[→ Try it live](https://dertill123.github.io/qonspekt/)**

Paste any article. Get 3–7 Obsidian-ready atomic notes with frontmatter, tags, and `[[wikilinks]]`. Download as `.zip`. Share via link. No account, no backend, no tracking.

![Qonspekt Demo](https://dertill123.github.io/qonspekt/demo.png)

## How it works

1. **Paste** any article, blog post, or paper
2. **Claude** extracts the key concepts and writes one atomic note per concept
3. **Download** as `.zip` or individual `.md` files — drag straight into Obsidian

## Features

- ⚛ **Atomic notes** — one concept per note, proper YAML frontmatter, `[[wikilinks]]`
- 🔐 **BYOK** — your Claude API key stays in your browser (`localStorage`), sent directly to Anthropic
- 🔗 **Share** — notes encoded in the URL hash, no server needed
- ⬇ **ZIP download** — ready for Obsidian, Logseq, Notion, any Markdown editor
- 💸 **~$0.003/article** with Claude Haiku 4.5
- 📱 **Mobile-ready** — works on any device

## Privacy

Qonspekt has **no backend**. Your API key and content are never sent to any server except the Anthropic API directly. There is nothing to log, store, or leak.

## Usage

Just open [qonspekt](https://dertill123.github.io/qonspekt/) in your browser.

Or run locally:

```bash
git clone https://github.com/DerTill123/qonspekt
cd qonspekt
open index.html  # or just double-click
```

No build step. No dependencies to install. It's one HTML file.

## Get a Claude API key

1. Go to [console.anthropic.com](https://console.anthropic.com/settings/keys)
2. Create a key (new accounts get free credits)
3. Paste it into Qonspekt — it's saved locally in your browser

## License

MIT
