---
name: deep-context-interview
description: Interviews the user (one question at a time, 14 blocks) to build "deep context" — how they like to work, who they are, family and key dates, sport, their company, people, contracts, finances, projects — and turns the answers into two claude.ai skills (my-profile, my-company) plus, where files are available, reference files ABOUT-ME.md and CONTEXT.md. Use when the user says "interview me", "deep context", "get to know me", "build my profile", "проведи інтерв'ю", "розпитай мене", "збери мій профіль", or wants Claude to stop asking the same background questions in every chat.
---

# Deep-context interview

Goal: after 2–4 sessions Claude knows the user well enough that no new chat has to ask "who is who, where things are, how do you like it". The result is saved as skills (work everywhere in claude.ai and Cowork) and, if possible, as files.

Speak the user's language (translate the questions below). Be warm and brief.

## 0. Before the first question
1. **Where am I?**
   - **Files available** (Claude Code, Cowork, or any environment where you can write files in the user's folder): you will write results to files after every block — section 4A.
   - **Plain claude.ai chat** (no file access): you keep the results in the conversation and hand over skills at the end — section 4B.
2. **Resume?** If the user pasted an "Interview progress" summary from an earlier chat, or `ABOUT-ME.md` / `CONTEXT.md` already exist, read them, say in one line where you continue, and skip what is answered.
3. Tell the user in 4–6 short lines how it works:
   - one question per message;
   - they can answer with text, voice, a file or a screenshot (CV, staff list, org chart, contract list); you will read it and skip questions it already answers;
   - commands: "next"/"skip", "block N", "pause";
   - **never** send passwords, card or account numbers, passport data or e-signature codes; contract numbers, names, positions and work phones are fine;
   - the whole interview takes 2–4 evenings and can be done in parts.
4. Ask which blocks to skip entirely (e.g. no company → skip 5–13; private person → skip 9–11).

## 1. How to ask
- **One question per message.** Wait for the answer.
- If the answer is incomplete, ask **one** short follow-up, then move on.
- At the start of each block say in one line which files would help (block 2 — CV; block 8 — staff list; block 10 — contracts).
- If something is already known (from earlier answers, a file, memory), show it as "Already know: …" so the user only corrects it, instead of asking again.
- "Look it up yourself": if you have file or mail access, search read-only and report what you found; otherwise say you can't and ask for the file.
- Tag every fact: **[user]** — they said it, **[document]** — from a file. Mark guesses as **[assumption]**.
- Never invent. Unknown stays unknown ("not answered").

## 2. The questions

### Block 1. How we work together
1. Which tasks do you give Claude most often, and which are the most important?
2. What annoys you most in answers: too long, too many questions, jargon, something else?
3. What may Claude do on its own, and what only after your "yes"? (messages, deletions, money, publishing)
4. Where do you usually work from: laptop, phone, a bot? Where do you prefer to receive results?
5. Which result formats suit you best: Excel, PDF, slides, Word, a messenger message?
6. Are there samples Claude must always use (letterhead, report to your boss, deck)? Where are they?
7. When do you usually work? When must you not be disturbed?
8. Whom may Claude write to on your behalf, and whom never?

### Block 2. About you
1. Full name. How to sign official letters?
2. Year of birth, education, previous jobs — what's worth knowing (a CV is ideal).
3. Languages: which one for partners? Your English level?
4. Hobbies?
5. Which principles must Claude follow (honesty, sources, checking regulations, …)?
6. What do you want to achieve in 1–3 years — personally and at work?

### Block 3. Family and home
1. Partner: what they do, how to address them, what may be sent to them on your behalf?
2. Children: kindergarten, school, activities, schedule.
3. Parents, siblings: names, where they live, how Claude can help them?
4. Which dates to remind you of: birthdays, anniversaries, other?
5. Home and utilities: who pays, how meter readings are sent?
6. Power during outages: generator, power station, power banks?
7. Car: model, mileage, next service, insurance expiry, VIN for parts?
8. Which household chores would you hand to Claude: shopping, prices, selling things?

### Block 4. Health and sport
1. Which sport, which watch and apps?
2. Upcoming races and goals.
3. Injuries or limits to take into account.
4. Help wanted with nutrition, weight, recovery?

### Block 5. The company: what it does
1. History: when founded, who built it, since when are you in your role?
2. Current state: what works, what doesn't, key monthly figures?
3. Technology or product: equipment, capacity, inputs, output.
4. By-products and waste: where do they go, are they sold?
5. Equipment that breaks most often.
6. Who services the equipment? Schedule, next overhaul?
7. Spare parts: where you buy, stock on hand, delivery time?
8. Addresses: legal, site, office. Where is accounting?

### Block 6. Market and sales
1. How and to whom do you sell: contracts, markets, intermediaries?
2. Tariffs and prices, how long they are valid, guarantees.
3. Who plans sales and volumes; what do forecast errors cost?
4. Grid / infrastructure connection: contracts, allowed capacity.
5. Metering: who reads the data, which meters or systems?
6. Current requirements from regulators and operators.
7. Regular reports: which, to whom, by which day?

### Block 7. Finance, bank, taxes
1. Loans: bank, balance, currency, rate, schedule, collateral, covenants, bank manager.
2. Agreements with the bank: what's agreed, which obligations?
3. Main monthly income and costs (order of magnitude is enough).
4. Accounting: who, which software, how to get trial balances?
5. Regular payments and their dates.
6. Taxes: system, VAT, regular returns, open issues with the tax office.
7. Insurance: what is insured, with whom, until when?
8. Audit: who and when?
9. Grants and state programs: at what stage?

### Block 8. People
1. How many employees, who works where?
2. Key people: name, position, responsibility, best way to reach them; nicknames/abbreviations you use.
3. What can be delegated to whom?
4. HR items to track (reservations, leave, certifications)?
5. Timesheets and payroll: who, what's needed from you?
6. Occupational safety: who is responsible, what's current?
7. Who is missing, open vacancies?
8. External consultants and lawyers: who is responsible for what?

### Block 9. Owner and related companies
1. How you work with the owner or your boss: how often you report, format, what they want to see first?
2. Which companies are in the group? What do you do in each?
3. Key people in those companies.
4. Settlements between the companies.
5. Folders with cryptic names: one line each — what it is, still relevant, may Claude open it?
6. Strategy: main decisions already made.
7. What you decide yourself and what only with the owner.

### Block 10. Counterparties and contracts
1. Without which 10 counterparties does the business stop? Who supplies what?
2. Key foreign partners: contracts, contact persons.
3. Supply and sales contracts: terms, prices, renewals.
4. Infrastructure and regulator contracts: numbers, dates, terms.
5. Construction/service contracts in progress: with whom, what stage?
6. Land or premises lease: plots, landlords, terms.
7. Which contracts expire soon or must be renewed?
8. Open disputes, claims, court cases, debts.
9. How you choose suppliers: quotes, tenders, approvals?
10. Keep a contract register with expiry dates and reminders?

### Block 11. State, regulation, security
1. Special statuses (critical infrastructure etc.): which, valid until when?
2. Licenses, reporting, inspections.
3. Environment: permits, reports.
4. Military registration / staff reservations: who is responsible?
5. Open cases with state bodies.
6. Site security: guards, shelter, backup power.
7. Which lawyers you have and whom to ask about what.

### Block 12. Projects in progress
1. All current projects by importance.
2. For each: next step and deadline.
3. What slows things down most?
4. New ideas you are seriously considering.
5. Who else works on each project?

### Block 13. Documents and files
1. Which folders are alive and which are archive?
2. Where are the letterhead, stamp and signature scans, letter and order templates?
3. How do you sign documents (no passwords)?
4. Which mailbox is for work and official letters?
5. Whom do you talk to about work in messengers?
6. Which documents are prepared monthly or quarterly — to make them from a template?

### Block 14. Projects with Claude and devices
1. Which of your Claude projects (bots, automations, apps) matter most, and which can be frozen?
2. Your devices: laptop, phone, tablet — models.
3. Which services do you pay for and how much are you willing to spend on IT per month?
4. Top 5 things to automate next (work and personal).

## 3. Commands
- **"next" / "skip"** — go to the next question.
- **"block N"** — jump to block N.
- **"pause"** — stop now. Save progress (4A) or print the progress summary (4B) and say how to resume.

## 4A. With file access — write after EVERY block
- Blocks 1–4 and 14 → `profile/docs/ABOUT-ME.md`; blocks 5–13 → `<company>/docs/CONTEXT.md` (ask the folder name once). Create folders if missing. Update sections in place instead of appending contradictions.
- Files the user sent: copy them to `profile/docs/sources/` or `<company>/docs/sources/` — **unless** they contain passwords, card numbers or passport data; then take only the facts.
- Keep a line "Interview: stopped at block N, question M" at the top of ABOUT-ME.md and update it on "pause".
- If there is a `CLAUDE.md` with a project table, add rows for these two files.

## 4B. In plain chat — keep it in the conversation
- After every block post a short **"Interview progress"** card: blocks done, key facts per block (bullets, with tags), where you stopped.
- On "pause" post one consolidated **"Interview progress"** block and tell the user: "To continue, open a new chat, say 'continue the interview' and paste this block."

## 5. At the end — build the skills
Fill two skills from the answers. Keep each under ~150 lines, concrete (names, dates, document numbers), no secrets:

- **my-profile** — sections: Who they are · Working rules (mandatory) · Result formats · Where and when · Personal. Description line: "Who <Name> is and how to work with them … Use this skill ALWAYS when <Name> asks for anything …".
- **my-company** — sections: Company · Current state · People and abbreviations (table) · Operations/sales · Finance · Group companies · Current projects · Open questions · Where files live. Description line: "Reference card for <Company> … Use ALWAYS when a task concerns <Company> …". Skip it if blocks 5–13 were skipped.

Each skill is a folder with one file: `my-profile/SKILL.md`, starting with YAML front matter (`name`, `description`).

Hand them over:
- **If you can create files** (Claude Code, Cowork, or claude.ai with file creation enabled): create `my-profile.zip` and `my-company.zip`, each containing `<name>/SKILL.md` (forward slashes inside the zip), and give them to the user.
- **Otherwise:** show each SKILL.md in its own code block and explain step by step: create a folder `my-profile`, save the text as `SKILL.md` inside it, compress the folder to `my-profile.zip` (Windows: right-click → Send to → Compressed folder).

Then tell the user how to install, step by step: claude.ai → their name (bottom left) → Settings → Capabilities → Skills → Upload skill → choose the zip → make sure it is switched on. If an older skill with the same name exists, delete it first. Cowork picks skills up automatically.

Finish with one line: what to re-run later (e.g. "say 'update my profile' when something changes — I'll ask only about what's new").
