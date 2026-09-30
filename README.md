# baba for ChatGPT and Claude

baba brings Hebrew and Israel news into your chat. Connect it to ChatGPT or Claude and ask for a Hebrew translation with its pronunciation, the nikud (vowel points) on a sentence, a name spelled in Hebrew letters, or a catch-up on today's news in Israel. The assistant calls baba, and baba answers with your baba account.

baba is made by [baba](https://www.itsbaba.com), the Hebrew translator app. Full details, limits and setup are at [itsbaba.com/ai-plugin](https://www.itsbaba.com/ai-plugin).

## Tools

| Tool | What it does |
| --- | --- |
| `translate` | Translates into or out of Hebrew, with pronunciation. Slang mode explains Israeli slang. |
| `add_nikud` | Adds nikud to Hebrew text, verified so the letters never change. |
| `transliterate` | Hebrew to Latin letters, or a Latin spelling to Hebrew letters. |
| `israel_top_stories` | The stories getting the most coverage across Israeli newsrooms now. |
| `search_israel_news` | Searches the last 30 days of Israeli news. |
| `israel_daily_brief` | baba News's Today in Brief. |

All tools only read. Translations count against your baba plan (free: 2,500 characters a month, baba Pro: 250,000). Nikud and transliteration allow 200 uses a day, and news 100 lookups a day.

## Install

**Claude Code**

```
/plugin marketplace add ZipLyne-Agency/baba-plugin
/plugin install baba@baba
```

Or connect only the server: `claude mcp add --transport http baba https://mcp.itsbaba.com/mcp`.

**Claude (claude.ai, desktop, mobile):** Settings, Connectors, then add baba from the directory, or choose Add custom connector and paste `https://mcp.itsbaba.com/mcp`.

**ChatGPT:** open the Apps directory, search for baba, and connect.

Each one opens a baba sign-in page (email code, Google or Apple) and asks you to allow the connection.

## Privacy and support

baba receives only what the assistant sends to a baba tool, not your conversation, and does not save plugin translations to your history. See the [privacy policy](https://www.itsbaba.com/privacy#ai-plugin) and [terms](https://www.itsbaba.com/terms#ai-plugin). Help: [itsbaba.com/support](https://www.itsbaba.com/support).
