# Emily Auto-Deploy Skill / Vercel Deployment Automation

God-mode auto deployment pipeline for Therapy Sausages, Forevermore, and the wealth empire.

## Native Vercel Git Integration (Recommended - Zero Config after setup)
1. Go to https://vercel.com/sausagetherapy/therapysausages/settings/git (or your project)
2. Connect Repository → select forevermore63/emily-auto-deploy-skill or sausage-therapy-platform
3. Every push to `main` deploys to production. Branches/PRs get preview URLs.

## GitHub Actions Method (this repo)
1. Create a Vercel Token: https://vercel.com/account/tokens
2. In this GitHub repo → Settings → Secrets and variables → Actions → New repository secret
   - Name: `VERCEL_TOKEN`
   - Value: the token
3. (Optional but better) Also add `VERCEL_ORG_ID` and `VERCEL_PROJECT_ID` from `.vercel/project.json` after linking.
4. Push to main or trigger "workflow_dispatch" → automatic production deploy.

## Agent / Chat Automation
We can also deploy any file tree instantly using the connected `vercel___deploy_to_vercel` tool (no Git required). Perfect for rapid iteration on the booking site.

## Next
- Link this or sausage-therapy-platform to the live therapysausages project.
- Add production code / improved booking page here.
- Set production domain if desired.

Built for perpetual wealth engine execution.
