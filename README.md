# amFOSS Member Directory: Your Onboarding Commit

onboard yourself into the club by making your first PR to this org, add yourself to the gihub org and the official amFOSS website's team page, by making your commit here

This repository serves as the roster for all current and past members of **amFOSS**, the Free and Open Source Software (FOSS) club of Amrita Vishwa Vidyapeetham, Amritapuri Campus. The data in this directory is used to generate the team page of the official amFOSS website.

## How to Contribute - Onboarding

To successfully add yourself to the org and the team page, create a Pull Request (PR) with the following two changes:

1.  **Add your Image**: Upload your professional image to the correct academic year folder within the `assets/` directory (e.g., `assets/first-years/your_name.jpg`).
2.  **Update `members.json`**: Add a new JSON object containing your profile details to the **end** of the member list in `members.json`.

## ⚙️ Automation

This repository uses GitHub Actions to automate key processes when changes are pushed to the `main` branch:

* **Automatic Organization Invitation**: A workflow runs after `members.json` is updated, identifying the GitHub username of the new member and automatically sending an invitation to join the `amfoss` GitHub organization.
* **Vercel Deployment Trigger**: A separate workflow automatically triggers a new Vercel deployment of the amFOSS website, ensuring your profile goes live immediately after the merge.
