# baba for ChatGPT and Claude

baba brings Hebrew, the way Israelis say it, into your chat. Connect it to ChatGPT or Claude and ask for a Hebrew translation with its pronunciation and the right form for a man or a woman, what an Israeli slang word means, a Hebrew sentence broken down word by word, ready phrases for a situation, the nikud on a sentence, or a catch-up on today's news in Israel. The assistant calls baba, and baba answers with your baba account.

In ChatGPT, baba answers with interactive cards (Listen, nikud toggle, word-by-word grid), has a home in the sidebar with a translator, the slang of the day and a phrasebook, opens a Hebrew helper beside any conversation, and keeps its settings on ChatGPT's own settings page.

baba is made by [baba](https://www.itsbaba.com), the Hebrew translator app. Full details, limits and setup are at [itsbaba.com/ai-plugin](https://www.itsbaba.com/ai-plugin).

## Tools

| Tool | What it does |
| --- | --- |
| `translate` | Translates into or out of Hebrew, with pronunciation and the right gender for speaker and listener. Slang mode explains street Hebrew. |
| `explain_israeli_slang` | baba's Israeli slang dictionary: meaning, pronunciation, usage, origin and examples. |
| `break_down_hebrew` | A Hebrew sentence word by word, with nikud, root, meaning and grammar. |
| `show_hebrew_phrases` | Hand-checked phrases for cafés, getting around, the shuk, meeting people, emergencies and texting. |
| `add_nikud` | Adds nikud to Hebrew text, verified so the letters never change. |
| `transliterate` | Hebrew to Latin letters, or a Latin spelling to Hebrew letters. |
| `israel_top_stories` | The stories getting the most coverage across Israeli newsrooms now. |
| `search_israel_news` | Searches the last 30 days of Israeli news. |
| `israel_daily_brief` | baba News's Today in Brief. |
| `update_settings` | Remembers your preferences: speaker gender, the language to translate Hebrew into, pronunciation and nikud. |

All tools only read, except `update_settings`. Translations count against your baba plan (free: 2,500 characters a month, baba Pro: 250,000). Nikud and transliteration allow 200 uses a day, and news 100 lookups a day.

## Install

**Claude Code**

```
/plugin marketplace add ZipLyne-Agency/baba-plugin
/plugin install baba@baba
```

Or connect only the server: `claude mcp add --transport http baba https://mcp.itsbaba.com/mcp`.

**Claude (claude.ai, desktop, mobile):** open [baba Hebrew in the Claude directory](https://claude.ai/directory/connectors/baba-hebrew) and choose Connect, or search for baba Hebrew under Customize, Connectors.

**ChatGPT:** in review for the ChatGPT plugin directory.

Each one opens a baba sign-in page (email code, Google or Apple) and asks you to allow the connection.

## Privacy and support

baba receives only what the assistant sends to a baba tool, not your conversation, and does not save plugin translations to your history. See the [privacy policy](https://www.itsbaba.com/privacy#ai-plugin) and [terms](https://www.itsbaba.com/terms#ai-plugin). Help: [itsbaba.com/support](https://www.itsbaba.com/support).
