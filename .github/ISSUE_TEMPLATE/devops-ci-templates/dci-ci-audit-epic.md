---
name: DevOps-CI - CI/CD Best Practices Audit Epic
about: Create an epic to hold tickets which will complete an audit. Occurs once per quarter.
title: '[Epic][Audit]: CI/CD Best Practices'
labels: 'epic,Audit,github-actions'
assignees: ''

---

## Audit Subject

### Description

Audit the CI/CD Workflows and GitHub repository settings to ensure best practices are being
followed and enforced. See the [Audit Criteria](#audit-criteria) for information on the items
to be checked.

Targeted Organization: *[<< GitHub Organization to Audit >>](<< URL linking to organization page >>)*

## Audit Criteria

- All workflow items are using pinned actions
- Appropriate permissions are set within the github workflows
- Dependabot is enabled on the repository
- The Repository is using self-hosted runners (if appropriate)
- The repository uses the current rulesets
- Individual branch protections are turned off
- Individual tag protections are turned off
- The Step-Security Hardened Security action is enabled
- CODEOWNERS is valid and up-to-date
- Teams are assigned to the repository
- Individual contributors that are part of assigned teams are removed from contributors list
- Actions are disabled if not in use within last 6 months
- [Repository settings](#repository-settings) are configured per organization standard
- All webhooks present are needed and in use
- *If Applicable*: Alert repository owners of software versions that are no longer supported
- *If Applicable*: Alert repository owners when software versions are within 3 months of losing support
- Custom properties: `last-ci-review-by-team` is set
- Custom properties: `last-ci-review-date` is set (Use format: `YYYY-MM-DD`)
- << Additional audit criteria >>

### Repository Settings

- [x] Require contributors to sign off on web-based commits
- [x] Features: Issues
- [x] Features: Preserve this Repository
- [x] Features: Discussions
- [x] Features: Projects
- [x] Pull Requests: Allow Squash Merging
- [x] Pull Requests: Always suggest updating pull request branches
- [x] Pull Requests: Automatically delete head branches
- [x] Pushes: Limit how many branches and tags can be updated in a single push

## Audit Filters

**[Items to be Audited](<< URL with github filter displaying all items to be audited >>)**

**[Audited Items](<< URL with github filter displaying all items which have been audited >>)**

```[tasklist]
## Subitems of this Epic

- [ ] << Audit story should be written for the following subitem >>
- [ ] << They should ideally be units of independent work that when completed are, on their own, valuable >>
- [ ] << Eventually these should be turned into a github audit user story to be described in detail, assigned, and worked. >>
```
