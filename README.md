# English Vocabulary Index

Static word-list site: 370,000+ English words with prefix/suffix search, topic lists, and user-created tick lists (e.g. `exclude` hides words). Data persists in localStorage.

## Files
- `index.html` — the app
- `words.js` — full word data (window.WORDS)
- `topics.js` — 26 topic word lists (window.TOPICS)
- `common.js` — ~83k everyday words ranked by how often people use them (window.COMMON), for word games like Finish The Word! that reject rare words
- `tools/build_common.py` — rebuilds `common.js` from [wordfreq](https://github.com/rspeer/wordfreq). Add words the game accepts to `EXTRA_WORDS` and re-run.

The **Words** dropdown picks how common a word must be (default: Common). **Sort** shows the most common words first.

Hosted via GitHub Pages. Update by pushing to `main`.
