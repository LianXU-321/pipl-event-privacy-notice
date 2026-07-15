# PIPL Event Privacy Notice

Codex skill for drafting, reviewing, and adapting short Chinese Personal Information Protection Law notices for activity registration and project application forms.

## What It Covers

- Event registration, startup competition, innovation award, roadshow, partnering day, project application, and collaboration opportunity forms
- Business contact information and project-material collection scenarios
- Form-field assessment and reusable notice adaptation
- Cross-border transfer notice and separate consent wording
- Optional marketing or follow-up activity consent wording
- Retention wording based on a retention determination method
- Plain-language checkbox text suitable for one-page forms

## Contents

- `SKILL.md` - main skill instructions and workflow
- `references/general-template.md` - reusable Chinese notice template and checkbox modules
- `references/usage-guide.md` - usage guidance and sample prompt
- `agents/openai.yaml` - Codex UI metadata

## Example Use

```text
Use $pipl-event-privacy-notice to draft a short Chinese personal information notice for an event registration or project application form.
```

Provide the activity type, handler name, exact form fields, whether project materials are uploaded, whether any overseas recipient is involved, the rights contact email, and whether later marketing or similar activity invitations are planned.

## Notes

Project names, project summaries, and pitch decks are not automatically personal information. They may contain personal information when they identify founders, team members, contacts, photos, resumes, emails, phone numbers, or individual project owners.

