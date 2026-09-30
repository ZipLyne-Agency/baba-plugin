---
name: baba-hebrew
description: Use baba for Hebrew. Translate into or out of Hebrew with pronunciation, add nikud, transliterate names, and look up current Israel news with the baba tools.
---

# Hebrew and Israel news with baba

Use the baba tools whenever the person works with Hebrew or asks about news in Israel.

- **Translate** into or out of Hebrew with `translate`. One side must be Hebrew. Pass `mode: "slang"` when the text is street Hebrew, slang or an idiom. Show the translation and the pronunciation it returns.
- **Nikud:** when someone wants to know how Hebrew is read, call `add_nikud` and show its output exactly. Do not add or change vowel points yourself.
- **Transliteration:** `transliterate` spells Hebrew in Latin letters (`he-to-latin`), or writes a name spelled in Latin letters in Hebrew letters (`latin-to-he`).
- **News:** `israel_top_stories` for what is happening now, `search_israel_news` for a topic, person or place, `israel_daily_brief` for a catch-up. Pass `lang: "he"` for Hebrew headlines. Link to the story pages the tools return.

Copy Hebrew from tool results exactly. When a tool reports that an allowance is used up, tell the person and do not retry.
