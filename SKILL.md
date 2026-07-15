---
name: pipl-event-privacy-notice
description: Draft, review, and adapt short Chinese Personal Information Protection Law notices for event registration, innovation award, startup competition, project application, partnering day, roadshow, and collaboration opportunity forms that collect business contact information and project materials from company representatives. Use when Codex needs to assess form fields, decide whether a reusable notice template fits, handle China PIPL notice items, cross-border transfer consent, optional marketing consent, retention wording, or user-friendly checkbox text for similar activity forms.
---

# PIPL Event Privacy Notice

Use this skill to produce concise, readable Chinese privacy notices for activity forms where a company collects business contact details and project or collaboration information from enterprise/startup participants.

## Core Workflow

1. Identify the scenario: event registration, project application, innovation award, startup competition, partnering day, roadshow, or partner recruitment.
2. Extract the facts before drafting:
   - personal information handler
   - activity name and business purpose
   - form fields and uploaded materials
   - service providers or co-organizers
   - overseas recipient, if any
   - rights contact email
   - whether later marketing/event invitations are planned
3. Classify the information:
   - business contact details are personal information when linked to an identifiable natural person.
   - company/project information is not automatically personal information, but may contain personal information if it identifies founders, team members, contacts, photos, resumes, emails, phone numbers, or individual project owners.
   - do not call all project materials personal information; instead cover both "personal information and project information" and warn users not to submit unnecessary third-party or sensitive personal information.
4. Draft with the short general template in `references/general-template.md`.
5. Add or remove modules:
   - Keep the overseas transfer paragraph and separate mandatory checkbox only when there is a real overseas recipient or overseas access.
   - Keep the marketing checkbox only when later event invitations, cooperation opportunities, or industry updates will be sent beyond the immediate activity.
   - Add service provider/co-organizer wording when a registration platform, event operator, project reviewer, or technical vendor helps process information.
6. Run the legal-item check before finalizing:
   - handler name
   - purpose
   - processing method
   - information categories
   - retention period or retention determination method
   - rights and contact method
   - entrusted processing or third-party provision, if applicable
   - cross-border recipient details and separate consent, if applicable
   - optional marketing consent, if applicable

## Drafting Rules

- Keep the notice short enough for a one-page form. Prefer plain Chinese over legalistic wording.
- Avoid over-limiting the purpose to one event type. Use "报名、申请或参与确认、活动通知、活动组织安排、项目筛选与评估、合作洽谈匹配及后续沟通" unless the facts require a narrower purpose.
- Use "实际收集的信息以本页面表单列明的字段为准" to keep the template adaptable.
- For retention, prefer a determination-method sentence instead of a fixed term unless the client has a settled retention rule.
- Do not overstate legal requirements:
  - location of an overseas recipient, such as "位于法国", is transparency-enhancing wording, not a mandatory standalone item under PIPL.
  - consequences of withdrawing consent are generally explanatory, not always necessary for a short form notice.
- For cross-border transfer, include at least recipient name, contact method, purpose, processing method, information categories, rights route, and a separate consent checkbox.
- In uploaded BP/project-material scenarios, include a friendly warning not to upload unrelated personal information, unauthorized confidential information, third-party personal information, or sensitive personal information.

## Output Format

For a drafting task, provide:

1. A short "个人信息处理告知" ready to paste onto the form.
2. Checkbox text:
   - mandatory general acknowledgement/consent
   - mandatory cross-border consent, if applicable
   - optional marketing consent, if applicable
3. A brief legal-item checklist confirming what is covered and what facts still need confirmation.

If the user asks whether an existing notice can be reused, answer in three parts:

1. whether the template fits
2. required substitutions
3. risks or missing facts

## References

- Read `references/general-template.md` when drafting or adapting a notice.
- Read `references/usage-guide.md` when the user asks how to package, share, or use this skill.
