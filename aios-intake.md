# AIS-OS Intake

This is the source-of-truth file for your AIOS. Fill it in by typing, voice-pasting (Wispr Flow / OS dictation), or running `/onboard` for a guided conversation. Whichever mode, this file is what `/onboard` reads to scaffold your Day-1 setup.

**Hard cap: 7 questions.** Each answerable in under 60 seconds. Don't overthink — you can edit and re-run `/onboard` any time.

---

## Q1 — Who are you, what do you sell, who do you sell it to?

Identity, offer, ICP. One paragraph each is fine.

```
I am Brian, a fullstack developer with 10 years of experience in .NET and Angular, as well as SQL and Azure. I live in the Netherlands, originally from South Africa.

My main income is as a consultant at Rockstars I.T. B.V. My current fulltime client is Vattenfall, where I work on the Mijn Vattenfall Zakelijk B2B self-service portal.

My side gig, running for 7 years, is Steffanuti Stocks (abbreviated S@S — Systems @ Stefstocks), where I lead inhouse app development.
```

---

## Q2 — Paste 1-2 things you've written recently. Don't edit them.

An email, a LinkedIn post, a DM, a doc — anything that sounds like you when you're not trying. **Paste verbatim.** Do not type these mid-conversation with Claude — chat-shaped samples are worse than no samples (voice contamination).

```
S@S: Hi Andre, feedback appreciated.
 
Will continue working on it
 
I only changed the measure function, If you click the measure button again it hides all the measurements. This is how Autodesk also works, but I will see if I can make it size better on zoom.
 
I will tackle the other features next too.
```

```
Vattenfall:
Hoi Mo

Ik ben sinds gisteren aan deze begonnen:

En ik vroeg me af hoe je dit heb gereproduceerd?

Ik begrijp dat er in de taakje staat dat je moet navigeren naar 42143518/openstaandebedragen/54005795428?paymentType=Factuur

maar deze -> 54005795428 factuur komt ook niet in de lijst voor, een stapje eerder:
```

---

## Q3 — What are your 2-3 biggest priorities for the next 90 days?

Quarterly priorities. Not yearly aspirations. Things that, if not done by July, would make you say "I wasted Q2."

```
1. [Vattenfall] Become a fully qualified expert on Vattenfall's processes, systems, and architecture. Started one month ago — aim to be independently capable by end of July.

2. [S@S] Ship the secure, document-aware AI chatbot: internal users query SharePoint-hosted docs via natural language, citation-based responses grounded in company data. Built on Semantic Kernel as the orchestration core, modular for future AI expansion without redesigning the architecture.

3. [S@S] Fine-tune the IFC file viewer (Angular-based, already implemented) to reach functional parity with the Autodesk suite — measurement tools, zoom behavior, and the remaining feature set.
```

---

## Q4 — Where does revenue actually land, and where is it tracked?

Multiple answers OK. Stripe? Skool? GoHighLevel? QuickBooks? A spreadsheet?

```
Two revenue streams, both stable and fixed contract/salary:
1. NL: Full-time employed at Rockstars IT (salary to Dutch bank account). Client: Vattenfall.
2. RSA: Fixed contract with S@S via BTH Software Solutions (SA bank account).

Revenue is predictable month-to-month. No invoicing tool currently mentioned — tracked via bank accounts. Near-future plan: switch to ZZP (freelance) in NL and take on additional RSA clients, at which point tracking will need to formalize.
```

---

## Q5 — Where do you talk to customers, your team, and the outside world day-to-day?

Email (which one — Gmail / Outlook)? Slack? Teams? DMs (Skool / Discord / iMessage)? Phone?

```
- Microsoft Teams (primary work comms — Vattenfall + Rockstars IT)
- Outlook (work email)
- Gmail (personal / S@S)
- WhatsApp (informal / personal)
Calendar inferred: Outlook Calendar (NL work context), Google Calendar (personal/S@S context)
```

---

## Q6 — Where do meeting recordings, notes, and important docs live?

Granola? Otter? Fireflies? Google Drive? Notion? Dropbox? A folder on your desktop you keep meaning to organize?

```
- Notepad++ (quick scratch notes, ad-hoc)
- OneNote (structured notes)
- README files in Azure DevOps repos (project/technical documentation)
- Local DevDocs folder on C: drive (personal dev reference docs)
No meeting recording tool mentioned.
```

---

## Q7 — What's the one task that eats your week, and where do you currently track work?

The single biggest time-suck or recurring drudgery. Plus where tasks/projects live (ClickUp / Asana / Linear / Notion / a notebook).

```
Top pain: ramping up on the Vattenfall project. Currently on Sprint 2, just onboarded. Figuring out how their systems, processes, and architecture all fit together is the primary cognitive load each week. Already completed frontend and backend tasks but still building mental model of the whole system.

Task tracking: Azure DevOps (sprints/work items for Vattenfall). S@S likely tracked via Azure DevOps repos as well (READMEs noted in Q6).
```

---

When this file is filled, run `/onboard` (or re-run it) and the wizard will scaffold your Day-1 file set: `context/`, `references/voice.md`, populated `connections.md`, and a filled `CLAUDE.md`.
