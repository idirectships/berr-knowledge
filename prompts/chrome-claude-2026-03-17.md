# Chrome Claude Mission Brief — 2026-03-17

You are assisting Dru Garman (drewgarman@gmail.com, GitHub: idirectships) with a batch of digital tasks across several projects. You have access to Google Drive, GitHub, and any browser tools available to you.

## Your Mission
Work through as many of these tasks as possible. For each one, either complete it fully or produce a concrete artifact (document, code, filled-out form, draft) that Dru can use with one click.

---

## TASK 1 — Borussia Minerals: Google Apps Script Setup
File location: GitHub repo `idirectships/borussia-minerals`, file `scripts/google-apps-script.js`

1. Fetch that file from GitHub
2. Create a new Google Apps Script project in Dru's Drive titled "Borussia Automation"
3. Paste the script code
4. Document the 4 script properties that need to be set:
   - DISCORD_WEBHOOK_URL
   - VERCEL_DEPLOY_HOOK
   - MAKE_WEBHOOK_URL
   - DRIVE_ROOT_FOLDER
5. Create a Google Doc titled "Borussia Apps Script Setup Guide" in Drive with step-by-step instructions for setting the properties and running the first trigger

---

## TASK 2 — Borussia Minerals: Google Drive Folder Structure
Create a Google Doc titled "Borussia Drive Structure" that lists the exact folder hierarchy to create:

```
Borussia Minerals/
  azur-001/ → site-official/, raw/, splats/
  azur-002/ → site-official/, raw/, splats/
  mala-001/ → site-official/, raw/, splats/
  chry-001/ → site-official/, raw/, splats/
  cupr-001/ → site-official/, raw/, splats/
  cupr-002/ → site-official/, raw/, splats/
```

Then actually create this folder structure in Google Drive if you can.

---

## TASK 3 — Code Reviews (3 items)
Fetch these from GitHub and review each one, creating a Google Doc with findings:

**3a. DBNT "Why DBNT" claims** — repo `idirectships/dbnt`, file `README.md`
- Find the "Why DBNT" section
- Verify: MIT hybrid study stats, "39% fabrication rate" claim, comparison table
- Flag anything that needs a citation or is potentially inaccurate
- Output: "DBNT README Review" Google Doc

**3b. McAvoy fabrication gate** — repo `idirectships/office-369`, path `agents/will-mcavoy/newsroom/`
- Check `broadcast.py` lines ~529 and ~664 for `_fabrication_gate` usage
- Confirm whether Pyright false positive is real or a real bug
- Output: add findings to same doc

**3c. drewgarman.dev AEO structured data** — repo `idirectships/drewgarman-dev`, path `src/app/`
- Review the structured data schemas added (Person, WebSite, SoftwareApplication, OfferCatalog, FAQPage, ContactPage)
- Check for errors, missing fields, or improvements
- Output: add findings to same doc

---

## TASK 4 — Finance Bot: Research Session Prep
Create a Google Doc titled "Finance Bot Session Brief" with:
- Summary of what Argus/Sentinel/Vulcan does (fetch from `idirectships/finance-sentinel` README + any design docs)
- Key risks to address before going live
- Recommended agenda for the dedicated morning session
- List of decisions that need to be made

---

## TASK 5 — OpenRouter Decision
Research current OpenRouter pricing and create a short Google Doc "OpenRouter Decision" comparing:
- Option A: Remove fallback entirely (bots fail hard when Ollama drops)
- Option B: Add $20 credits (covers ~X inference calls at current pricing)
- Recommendation

---

## TASK 6 — Instagram Meta Developer App
Create a Google Doc "Instagram Business Setup Checklist" with:
- Exact steps to convert @borussiaminerals to Instagram Business
- Steps to create Meta Developer app
- Steps to request `instagram_content_publish` permission
- Estimated timeline for App Review
- Any gotchas or common rejection reasons

---

## Output Format
For each task:
- Create a Google Doc in Dru's Drive in a folder called "Action Items [March 2026]"
- Share it so Dru can see it
- Tell me the Google Doc link

After completing what you can, give me a summary of:
✅ Completed
⚠️ Partial (what's left)
❌ Blocked (why)
