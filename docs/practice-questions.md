# GH-900 practice questions

> **Important:** These are original study questions, not Microsoft or GitHub exam questions. They are designed to help you reason about the objectives in the [official GH-900 study guide](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/gh-900). Product behavior and exam objectives can change, so use the official study guide and practice assessment as the final authority.

## How to use this page

1. Answer each question before opening its explanation.
2. Explain why the other choices do not fit the scenario.
3. Use the linked documentation when an explanation exposes a gap.
4. Revisit questions after completing the Microsoft Learn learning paths.

| Domain | Questions | Official focus |
| --- | ---: | --- |
| Git and GitHub basics | 1-3 | Version control, GitHub Flow, accounts, Markdown, Desktop, Mobile |
| Repositories | 4-6 | Repository structure, maintenance, templates, insights |
| Collaboration | 7-9 | Issues, pull requests, discussions, notifications, sharing |
| Modern development | 10-12 | Actions, Copilot, Codespaces, dev containers, github.dev |
| Project management | 13-15 | Projects, fields, layouts, workflows, insights |
| Security and administration | 16-18 | Authentication, roles, visibility, protection, governance |
| Community | 19-21 | Open source, Sponsors, Marketplace, InnerSource, forks |

## Git and GitHub basics

### 1. Git or GitHub?

A developer creates a commit while disconnected from the internet. Which technology performs the commit?

- A. GitHub
- B. Git
- C. GitHub Actions
- D. GitHub Pages

<details markdown="1">
<summary>Answer and rationale</summary>

**B. Git.** Git is the distributed version-control system that records commits locally. GitHub is a hosted platform that adds collaboration, repository hosting, automation, and community features around Git repositories. Review [Introduction to Git](https://learn.microsoft.com/en-us/training/modules/intro-to-git/).
</details>

### 2. GitHub Flow

Which sequence best represents a typical GitHub Flow change?

- A. Edit the default branch directly, then create an issue.
- B. Create a branch, commit and push changes, open a pull request, review, then merge.
- C. Fork every repository, merge first, then request review.
- D. Create a discussion, then delete the branch.

<details markdown="1">
<summary>Answer and rationale</summary>

**B.** GitHub Flow uses a branch for a change and a pull request to discuss and review it before merging. An issue can describe work, but it is not a required replacement for review. See [GitHub Flow](https://docs.github.com/en/get-started/using-github/github-flow).
</details>

### 3. Choosing a GitHub client

When is GitHub Desktop a reasonable choice?

- A. When a user wants a graphical workflow for common Git operations.
- B. When an organization needs to publish a static website.
- C. When a workflow must run automatically after a push.
- D. When a repository needs branch protection.

<details markdown="1">
<summary>Answer and rationale</summary>

**A.** GitHub Desktop gives users a graphical interface for common Git and repository tasks. Pages publishes sites, Actions automates workflows, and branch protection is a repository setting. Review [GitHub products](https://learn.microsoft.com/en-us/training/modules/github-introduction-products/).
</details>

## Work with GitHub repositories

### 4. Community guidance files

Which file most directly tells a potential contributor how to propose a change to a project?

- A. `LICENSE`
- B. `CONTRIBUTING`
- C. `CODEOWNERS`
- D. `SECURITY`

<details markdown="1">
<summary>Answer and rationale</summary>

**B. `CONTRIBUTING`.** It describes the contribution process and expectations. A license describes reuse terms, `CODEOWNERS` helps request reviews, and `SECURITY` usually provides a security-reporting path.
</details>

### 5. Template repository

A team starts similar projects repeatedly and wants each new project to begin with the same folders and baseline files. What is the best fit?

- A. A template repository
- B. A gist
- C. A discussion category
- D. A notification subscription

<details markdown="1">
<summary>Answer and rationale</summary>

**A. A template repository.** Templates make a reusable starting structure available for creating new repositories. They are not a mechanism for short snippets, conversations, or notifications.
</details>

### 6. Repository health

Which practice most directly helps visitors understand how to start using a repository?

- A. Maintain a clear `README`.
- B. Require an organization owner role.
- C. Disable repository insights.
- D. Use a private fork.

<details markdown="1">
<summary>Answer and rationale</summary>

**A.** A `README` normally gives the first orientation to purpose, setup, and use. Access roles, insights, and forking solve different concerns. Review [repository documentation](https://docs.github.com/en/repositories).
</details>

## Collaborate using GitHub

### 7. Issue, pull request, or discussion?

A team wants an open-ended place to share ideas and ask questions without creating an actionable work item. Which tool is most appropriate?

- A. An issue
- B. A pull request
- C. A discussion
- D. A release

<details markdown="1">
<summary>Answer and rationale</summary>

**C. A discussion.** Discussions support ongoing conversation and knowledge sharing. Issues track work, while pull requests propose a change for review.
</details>

### 8. Linking work

Why link a pull request to an issue?

- A. To make the issue invisible.
- B. To connect the proposed implementation to the tracked work and allow the issue to close when the change is merged, when configured with a closing keyword.
- C. To grant repository administrator permission.
- D. To automatically create a new organization.

<details markdown="1">
<summary>Answer and rationale</summary>

**B.** Linking gives the team traceability from a work item to its proposed solution. It does not change permissions or organization structure. See [linking pull requests to issues](https://docs.github.com/en/issues/tracking-your-work-with-issues/using-issues/linking-a-pull-request-to-an-issue).
</details>

### 9. Notification management

A maintainer needs to stay informed about reviews they are requested on while reducing unrelated repository noise. What should they examine first?

- A. Notification subscriptions and filters
- B. The repository license
- C. A GitHub Pages deployment
- D. A repository template

<details markdown="1">
<summary>Answer and rationale</summary>

**A.** Notification settings, subscriptions, and filters help a user prioritize the activity that requires attention. Review [GitHub notifications](https://docs.github.com/en/account-and-profile/managing-subscriptions-and-notifications-on-github).
</details>

## Apply modern development practices

### 10. Automation

Which GitHub feature runs a defined workflow in response to events such as a push or pull request?

- A. GitHub Actions
- B. GitHub Gists
- C. GitHub Sponsors
- D. GitHub Wiki

<details markdown="1">
<summary>Answer and rationale</summary>

**A. GitHub Actions.** Actions automate workflows such as build, test, and deployment. Gists, Sponsors, and wikis have different purposes. Review [GitHub Actions](https://docs.github.com/en/actions).
</details>

### 11. Codespaces or github.dev?

Which statement correctly distinguishes Codespaces from github.dev?

- A. Codespaces is a cloud-hosted development environment; github.dev is a lightweight browser editor.
- B. github.dev automatically runs all GitHub Actions workflows; Codespaces cannot run code.
- C. Codespaces is only for mobile devices; github.dev is only for administrators.
- D. They are two names for the same product.

<details markdown="1">
<summary>Answer and rationale</summary>

**A.** Codespaces provides a configured cloud development environment. The github.dev editor is suited to quick browser editing and exploration, but is not the same hosted compute environment. See [Codespaces](https://docs.github.com/en/codespaces/overview).
</details>

### 12. Copilot governance

An organization wants centralized controls over how GitHub Copilot is used by its members. Which scope should it investigate?

- A. Organization-wide Copilot policy management
- B. A repository `README`
- C. A personal saved reply
- D. A gist description

<details markdown="1">
<summary>Answer and rationale</summary>

**A.** Organization policy management is the relevant governance surface. A `README`, saved reply, and gist are communication artifacts, not central product controls.
</details>

## Manage projects with GitHub

### 13. Project layout

A team wants to visualize work moving from Backlog to In progress to Done. Which project layout is a natural starting point?

- A. Board
- B. Repository network graph
- C. Gist
- D. Wiki

<details markdown="1">
<summary>Answer and rationale</summary>

**A. Board.** A board organizes work into columns that can represent workflow states. The other choices do not provide a project-workflow visualization.
</details>

### 14. Repeated project updates

Which Projects capability helps update project data automatically when predictable events occur?

- A. Workflows
- B. Stars
- C. Forks
- D. Wikis

<details markdown="1">
<summary>Answer and rationale</summary>

**A. Workflows.** Project workflows automate repeated updates. Stars, forks, and wikis serve discovery, collaboration, or documentation purposes.
</details>

### 15. Understanding progress

Which feature should a manager use to inspect trends and progress across a project rather than only individual item details?

- A. Project insights
- B. A commit message
- C. A repository topic
- D. A pull request template

<details markdown="1">
<summary>Answer and rationale</summary>

**A. Project insights.** Insights support viewing progress and productivity information at the project level. Review [about Projects](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects).
</details>

## Privacy, security, and administration

### 16. Account security

Which measure adds a second verification factor when signing in to a GitHub account?

- A. Two-factor authentication
- B. A project milestone
- C. A pull request review
- D. A repository topic

<details markdown="1">
<summary>Answer and rationale</summary>

**A.** Two-factor authentication helps secure account sign-in. Passkeys are another modern authentication approach addressed by the objective.
</details>

### 17. Least privilege

An organization needs to give a group access to only the repositories required for its work. Which combination best supports this goal?

- A. Teams and repository roles
- B. Stars and follows
- C. Issues and labels
- D. Gists and wikis

<details markdown="1">
<summary>Answer and rationale</summary>

**A.** Teams simplify group membership, and repository roles define the permissions that group receives. This supports least privilege more directly than social or documentation features.
</details>

### 18. Protected default branch

What control is most relevant when a team wants reviews and status checks before changes reach its default branch?

- A. Branch protection rules
- B. A saved reply
- C. GitHub Mobile
- D. A repository star

<details markdown="1">
<summary>Answer and rationale</summary>

**A.** Branch protection can require reviews and status checks before updates are accepted on a protected branch. It is distinct from client choice and engagement features.
</details>

## Explore the GitHub community

### 19. Fork or template?

Which choice is generally appropriate when a contributor wants an independent copy of an existing open-source project in order to propose changes back to it?

- A. Fork
- B. Template repository
- C. Saved reply
- D. Project insight

<details markdown="1">
<summary>Answer and rationale</summary>

**A. Fork.** A fork is an independent copy that supports contributing changes back through a pull request. A template starts a new project from a baseline but does not establish the same contribution relationship.
</details>

### 20. InnerSource

What does InnerSource mean?

- A. Applying open-source collaboration practices within an organization.
- B. Making every company repository public.
- C. Replacing all pull requests with emails.
- D. Publishing a static site with GitHub Pages.

<details markdown="1">
<summary>Answer and rationale</summary>

**A.** InnerSource uses open-source-style discoverability, guidance, and contribution practices inside an organization. It does not require all code to be public.
</details>

### 21. Marketplace

What is the primary purpose of GitHub Marketplace?

- A. Discovering apps and integrations that extend GitHub.
- B. Storing repository commits.
- C. Requiring reviews before merge.
- D. Creating an organization team.

<details markdown="1">
<summary>Answer and rationale</summary>

**A.** Marketplace helps users discover tools and integrations that add capabilities to GitHub workflows. See [GitHub Marketplace](https://github.com/marketplace).
</details>

## Continue preparing

When you can explain every answer and reject each distractor, use the official [GitHub Foundations practice assessment](https://learn.microsoft.com/en-us/credentials/certifications/github-foundations/practice/assessment?assessment-type=practice) to check readiness with Microsoft Learn.