# Governance

## Ownership and authority

The DevImpact GitHub organization is administered by its designated owner account, `shelternewlife`. The organization owner is responsible for approving structural changes and deciding which projects or resources are officially part of the organization.

Repository permissions must follow the minimum access needed for each task. No additional members or teams should be added without explicit approval.

## Decision-making

The following changes require explicit owner approval:

- Creating or deleting an organization repository.
- Changing repository visibility or ownership.
- Adding members, teams, outside collaborators, or applications.
- Enabling or changing GitHub Actions and other automation.
- Connecting external services or introducing paid infrastructure.
- Publishing private or internal material.
- Changing the approved five-repository structure.

Routine documentation improvements may be made within the existing public documentation repository, provided they do not change these boundaries.

## Repository boundaries

The five approved repositories have separate responsibilities:

| Repository | Visibility | Responsibility |
|---|---|---|
| `devimpact.github.io` | Public | Main public website |
| `world-core` | Private | Internal core information and standards |
| `world-directory` | Public | Public directory of projects |
| `world-docs` | Public | Public documentation |
| `world-roadmap` | Private | Internal planning |

Private repository contents must not be copied into public repositories unless reviewed and explicitly approved for publication.

## Change management

- Use the `main` branch for approved work.
- Keep changes focused and review the affected files before committing.
- For a discrete documentation task, prefer one coherent commit.
- Do not create pull requests, branches, tags, releases, or automation runs unless the owner requests them.
- Do not rewrite history or force-push as a routine practice.

## Accuracy

Public statements must distinguish verified facts from plans or proposals. Do not describe planned features as completed, imply partnerships that do not exist, or make legal or commercial claims without an appropriate basis.
