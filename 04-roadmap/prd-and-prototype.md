# PRD & Prototype Sprint (Module 4)

## Pick & scope with MoSCoW
- **The “Now” feature I’m scoping (name + one-line core description):** One-Click Compliance Checklist (B1): A simplified, pre-filled compliance checklist that enables dispatch coordinators to verify driver readiness, complete mandatory checks and approve drivers for dispatch quickly and accurately.
- **My finalized Must-Haves (after overriding the AI):** Display mandatory compliance checks;  allow coordinators to confirm each check; prevent dispatch approval when required checks are incomplete; show clear completion status. restrict access to authorised users.
- **What I demoted from Must → Should/Won’t, and why:** Pre-fill available driver information. I removed this because of data protection and privacy.

## Generate your Simplified PRD
- **One thing my PRD makes explicit that a vague brief would have missed:** My PRD explicitly defines that dispatch approval must remain disabled until every mandatory compliance check has been manually confirmed. It also excludes automatic pre-filling of driver information to minimise data privacy risks. A vague brief might have focused only on speeding up the process without specifying these essential safety and approval controls.

## Prompt-to-prototype sprint
- **Where did the prototype reveal a gap in my PRD logic? (what I had to update):** testing the prototype highlighted the need to make the handling of incomplete compliance checks more explicit. Although my PRD required all five checks before dispatch approval, I needed to clarify how the interface should communicate outstanding requirements, prevent premature approval and handle changes to previously confirmed checks.
- **My prototype, as a link or a screenshot (publish or share from your tool; in Lovable that is Share → Share Preview, in Bolt Publish → Web. No share URL? Screenshot the working flow):** https://lovable.dev/preview/Kf2SKzSewuyxf0CUDyrOOlJdu1xeNKR5
