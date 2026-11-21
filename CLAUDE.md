# Book-to-skill pipeline: standing preferences

These are the user's standing instructions for turning books (Google Drive links) into Claude skills.

- **Deliver right away.** As soon as a skill is packaged (`skills-packaged/<name>.skill`), send the `.skill` file with SendUserFile. Do not wait for evals to finish. The user wants every new skill saved, so they can press **Save skill** on the card. Claude cannot save a skill to the user's claude.ai account itself.
- **Install locally.** Install every new skill in `.claude/skills/<name>/` so this repo's sessions can use it at once.
- **Evals.** Run the standard pipeline: 3 evals with 6 assertions each, with and without the skill. Grade every assertion with real evidence and build the review page. Advanced retests live in `skills-workspace/<name>/iteration-2/` (from `evals-advanced.json`).
- **Report honestly.** Report scores honestly, including when a well-known book gains little from its skill.
