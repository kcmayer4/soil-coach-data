# soil-coach-data

Remote content for the Living Soil Coach app — suppliers & learnings.

The app fetches these JSON files at runtime, so **content updates need no app
rebuild**: edit a file, `git push`, and the change shows up on the next app launch.

- `suppliers.json` — regional sourcing directory (base: 15755 Teupitz)
- `learnings.json` — captured sourcing/quality/material/tech learnings

Both files carry `{de, en}` for every note/text. `version` bumps on schema
changes; `updated` is the content date.
