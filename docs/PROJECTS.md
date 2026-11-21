# Projects and Repository Structure

## Organization repositories

The DevImpact organization is intentionally limited to the following five repositories.

### 1. `devimpact.github.io`

- Visibility: Public
- Purpose: The main DevImpact website.
- Expected content: Public introduction, ecosystem overview, and links to official resources.

### 2. `world-core`

- Visibility: Private
- Purpose: Internal core information, shared standards, and material that is not intended for public release.
- Handling: Do not publish its contents without explicit review and approval.

### 3. `world-directory`

- Visibility: Public
- Purpose: The public catalog of projects associated with the DevImpact ecosystem.
- Public directory: https://devimpact.github.io/world-directory/
- Source repository: https://github.com/DevImpact/world-directory
- Expected content: Project descriptions and links to their canonical repositories and product pages.

### 4. `world-docs`

- Visibility: Public
- Purpose: Official documentation, governance guidance, and contribution and security practices.
- This repository is the source for the documents in this folder.

### 5. `world-roadmap`

- Visibility: Private
- Purpose: Internal planning and prioritization.
- Handling: Roadmap details remain private unless the owner approves a public summary.

## Canonical project information

Use the [public World Directory](https://devimpact.github.io/world-directory/) as the canonical public index of individual projects. Its [source repository](https://github.com/DevImpact/world-directory) contains the directory implementation and structured catalogue. Avoid maintaining competing project lists in multiple repositories.

A project should be described accurately and linked to its authoritative source. Do not imply that a project is hosted inside the DevImpact organization when its repository is owned elsewhere.

## Adding a project

Before adding a project to the public directory:

1. Confirm the project name and canonical repository.
2. Confirm that the destination and any linked pages are publicly accessible.
3. Verify the description and product links.
4. Avoid publishing credentials, private data, or unapproved claims.
5. Update the directory in accordance with its own contribution guidance.

Adding a project to the directory does not automatically authorize creating a new DevImpact organization repository.
