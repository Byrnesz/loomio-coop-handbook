# Read Me
```markdown name=README.md
# Loomio Co-op Handbook

A comprehensive handbook documenting the organizational practices, governance, and processes of the Loomio worker-owned cooperative.

## What This Is

The Loomio Co-op Handbook is an open-source guide to running a democratic, worker-owned technology cooperative. Originally written circa 2016 as a detailed record of how Loomio operates, it's preserved here as both a functional reference and a model for other organizations seeking to build transparent, cooperative structures. The handbook covers governance principles, employment practices, decision-making workflows, and the philosophy behind building software for collaborative decision-making.

## Stack

- **Language:** Markdown documentation
- **Build Tool:** mdBook (configured in `book.toml`)
- **Format:** Static site generator for publishing organized technical documentation
- **CI/CD:** GitLab CI for automated builds (`.gitlab-ci.yml`)

## How It's Organized

```
src/
  README.md                          Introduction and context
  SUMMARY.md                         Table of contents structure
  
  [Our Cooperative Section]
    our_cooperative.md              Overview of the co-op
    history.md                      Origins and evolution of Loomio
    purpose_and_vision.md           Mission and values
    cooperative_principles.md       Co-op philosophy
    constitution.md                 Legal governance document
    governance.md                   Governance framework
  
  [Working Together Section]
    working_together.md             How the team organizes
    strategy.md                     3-year strategic planning
    planning.md                     Quarterly planning cycles
    sprints.md                      2-week sprint cycles
    coordination.md                 Coordinator role and responsibilities
    working_groups.md               Team structure and working groups
    product_prioritisation.md       Product development process
    using_loomio.md                 Internal use of Loomio tool
    communications.md               Internal communication tools
    marketing_tools.md              External communication resources
    dev_tools.md                    Development tooling
  
  [People & Culture Section]
    looking_after_people.md         People support overview
    stewarding.md                   Mentorship and stewardship
    well_working_group.md           Wellbeing initiatives
    professional_development.md     Learning and growth
    conflict_resolution.md          Dispute resolution process
    conflict_resolution_resources.md Additional resources
    retreats.md                     Team retreats
    staff_wellbeing_budget.md       Wellbeing funding
  
  [Employment & Membership Section]
    employment_and_membership.md    Overview
    employment.md                   Employment policies
    staff_onboarding.md             Onboarding process
    membership.md                   Membership pathway
    loomio_points.md                Equity/compensation system
    health_and_safety.md            Health and safety guidelines
    annual_leave.md                 Leave policies
  
  [Other Guides Section]
    guides.md                       Additional resources
    bug_reporting_guidelines.md     Bug reporting standards
    community_group.md              Community engagement
    brand_guidelines.md             Brand and messaging
    collaborative_funding.md        Funding models
    inspiration.md                  References and inspiration
  
  img/                              Images and diagrams
  [Various images]                  Organization charts, planning diagrams
```

## How It Fits Together

The handbook represents Loomio's full operational model organized into five main sections. The cooperative foundation (governance, constitution, principles) establishes the values and legal structure. The "Working Together" section details how decisions flow through quarterly planning → sprint execution via coordinators and working groups. The "Looking After People" section shows how the co-op supports members through stewardship, conflict resolution, and professional development. Employment & Membership documents the pathways for joining and the practical systems (equity points, leave policies, onboarding). This creates a complete picture of a bossless organization that uses "dynamic hierarchies by consent"—delegating specific roles while keeping ultimate authority with the membership.

## How to Run It

This is a documentation site, not a running application.

**To build and view the handbook locally:**

```bash
# Install mdBook if you don't have it
cargo install mdbook

# Navigate to the repo directory
cd loomio-coop-handbook

# Build the site
mdbook build

# Serve locally (opens in browser at http://localhost:3000)
mdbook serve
```

The built site will be generated in the `book/` directory and deployed via GitHub Pages.

**To contribute:**

1. Edit the relevant `.md` file in `src/`
2. Update `src/SUMMARY.md` if adding new pages
3. Build locally to verify your changes: `mdbook serve`
4. Open a pull request with your changes

## Try Asking

- **How does Loomio handle coordination without traditional managers?** See [coordination.md](src/coordination.md) for details on the "dynamic hierarchies by consent" model and coordinator responsibilities.

- **What's the membership pathway and how does equity work?** Check [membership.md](src/membership.md) and [loomio_points.md](src/loomio_points.md) for the system of becoming a member and the Loomio Points equity compensation model.

- **How are conflicts resolved in a cooperative?** Read [conflict_resolution.md](src/conflict_resolution.md) and [conflict_resolution_resources.md](src/conflict_resolution_resources.md) for the escalation process and support resources.

---

**License:** [Creative Commons Attribution-ShareAlike 4.0 Unported License](http://creativecommons.org/licenses/by-sa/4.0/)

**More Info:** Visit [loomio.coop](http://loomio.coop) for more about Loomio, or [loomio.com](https://www.loomio.com) to try the software.
```
