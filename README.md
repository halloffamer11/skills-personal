# Personal Pack

Procedures only. Account details, addresses and records stay on each Machine.

| Skill | What it does |
|---|---|
| `facebook-marketplace` | Research, price, draft and post a listing. The seller approves the filled form before it is published. |
| `google-access` | Read Gmail, Calendar, Drive, Docs, Sheets, Contacts and Tasks through the `gog` CLI, read-only. Accounts are gog aliases set on each Machine (`gog auth alias set <alias> <email>`). |

Install with the skills CLI:

```sh
skills add halloffamer11/skills-personal -g -s facebook-marketplace google-access -a claude-code codex antigravity-cli
```
