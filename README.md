# SIP Clarity — No-API fallback

Runs without an OpenAI API key, paid credits, or external AI service.

- SIP Clarity uses keyword-based retrieval against a small curated set of public Groww help pages.
- Feedback Discovery Engine uses predefined keyword rules to classify pasted statements.
- This is a deterministic, rule-based prototype, NOT a generative AI system. Do not claim outputs are AI-generated or report model accuracy. Human review is required.
- The source corpus is limited and should be expanded and verified.

## Replace your project
1. Stop the dev server with Ctrl+C.
2. Back up your current project folder.
3. Extract this ZIP and copy its contents into your current project folder, replacing files when prompted.
4. `.env.local` is no longer needed. Delete it locally and revoke any API key exposed in screenshots. Never commit secrets.
5. Run `npm run dev` and test both tabs.

## Deploy
Push to GitHub and import into Vercel as a Next.js project. No environment variables are required.
