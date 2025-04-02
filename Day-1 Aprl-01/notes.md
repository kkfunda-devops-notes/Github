✅ Step 1: Create a GitHub Account
Email: kkeducationblr@gmail.com

Password: Use a strong, unique password (e.g., P@a12345).

Username: kkeducation1234567

Public URL: https://github.com

Enterprise URL: https://airtel.github.com

Best Practices:

Use strong passwords for all accounts.

Enable Two-Factor Authentication (2FA) for added security.

✅ Step 2: Log in to GitHub
Navigate to GitHub Login.

Enter your credentials.

Once logged in, you will be directed to your GitHub dashboard, where you can begin creating and managing repositories and organizations.

✅ Step 3: Create an Organization
An organization allows you to manage projects and team access. Follow these steps to create your organization:

Organization Name: bsnl-4g-test

Service Accounts (NOT personal emails):

❌ kkeducationblr@gmail.com (personal)

❌ prasanth@bsnl.com (personal)

✅ devops4g@bsnl.com (service account)

Why use service accounts?
Service accounts are used for automated processes (CI/CD pipelines, bots, etc.), minimizing the security risks associated with personal email accounts.

✅ Step 4: Create Repositories
Repositories are the core of GitHub, where your project code and history are stored.

Private Repository: testing-private-repo
Used for internal or restricted-access projects.

Public Repository: testing-public-repo
Open-source projects, visible to everyone.

Additional Notes:

You can create repositories with either a README file (to initialize the repo) or without.

GitHub Pages: You can host static websites directly from your repositories.

✅ Step 5: Create Teams
Teams help you organize users based on their roles and responsibilities. Create teams and assign appropriate repository access.

Example teams:

Dev Team: bsnl-dev-team

DevOps Team: bsnl-DevOps-Team

QA Team: bsnl-qa-team

SRE Team: bsnl-sre-team

DB Team: bsnl-db-team

Each team should have specific access privileges based on their role in the project.

✅ Step 6: Add Users to Teams
Add users to your created teams based on their roles. You can add them using either GitHub usernames or verified email addresses.

Example:

Dev Team: Developers

DevOps Team: Infrastructure/Automation Engineers

QA Team: Quality Assurance Engineers

SRE Team: Site Reliability Engineers

DB Team: Database Administrators

✅ Step 7: Grant Repository Access to Teams
Once teams are created, assign them access to the repositories based on their needs:

Read Access: Can view the repository.

Write Access: Can clone, pull, and push changes.

Admin Access: Full control (ability to modify settings, add collaborators, etc.).

Example access setup:

Devs: Read/Write access

DevOps: Admin access

QA: Read access

DB: Read/Write access

Tip: Always be cautious when assigning Admin rights. Limit it to trusted team members who need full control.

✅ Step 8: Manage Access & Clean-up
As your project evolves, you may need to update permissions, delete unnecessary repositories, or remove users.

Change Visibility: You can change the visibility of a repository (Public ↔ Private) at any time under Repository Settings.

Delete Repositories, Teams, Users, or Organizations: These can be deleted if no longer needed, but ensure you back up any data before deletion. Deletion is permanent.

Transfer Ownership: If you need to move a repository to another organization or user, GitHub provides a simple process for this.

Best Practices for Security & Maintenance:

Review access regularly to ensure no unnecessary permissions are granted.

Enable Branch Protection Rules to enforce code reviews before merging changes.

Set up Webhooks or GitHub Actions for automation (e.g., for CI/CD, deployments).

Audit Logs: Regularly review logs for suspicious activity or unauthorized access.

Additional Best Practices
Branch Protection: Protect critical branches (e.g., main or develop) by requiring pull requests and reviews before merging changes.

Code Reviews: Enforce mandatory code reviews on pull requests to maintain code quality.

Automate with GitHub Actions: Set up workflows for continuous integration and deployment, automate testing, or trigger notifications.

Service Accounts for Automation: Use service accounts for automated systems (e.g., CI/CD pipelines), instead of using personal credentials.

Regular Audits: Periodically review audit logs for access tracking to ensure compliance and security.

Useful Links
GitHub Docs

Git CLI Cheat Sheet

GitHub Actions Documentation
