<!-- When opening a PR: 
- Find a reviewer as soon as possible and notify them 
- Convert the PR to a draft until it's ready for review
- Link to any relevant issue, document, discussion...
- Use all relevant section of this template, delete the rest. Requested sections are: Context, Description, Developer checklist and Instructions for reviewer.
- Once ready for review, tag the reviewer
--> 

# Clear title 

## Context 

<!-- 
Describe **why** this PR is needed
Example: 
- Function blah() is to slow
- Deprecated use of bloop()
-->

## Description 

<!-- 
Describe **what** changes were made - ideally this is the same content as the corresponding NEWS.md

Example: 
- Performed some bench-marking (link to relevant document if any)
- Used this package to optimize blah(), it's now 15x faster 
- replaced bloop() with more up to date function
-->

Type of change (select 1):
- [ ] Bug fix (non-breaking change which fixes an issue)
- [ ] New feature (non-breaking change which adds functionality)
- [ ] New tests (no changes made to the code)
- [ ] New documentation (no changes made to the code)
- [ ] Breaking change (fix or feature that would cause existing functionality to not work as expected)

Versioning: 
- [vx.x.x -> vx.x.x]

## Related issues 

<!-- 
Mention all related issues 

Example:
- Closes [reference issue]
- Closes [reference issue]
-->

## Developer checklist 

- [ ] All conflicts are resolved
- [ ] You have run `devtools::document()` without error 
- [ ] You have run `devtools::check()` without error
- [ ] Tests are implemented or modified to reflect the changes
- [ ] Functions are documented and reflect the changes made in this PR
- [ ] The `DESCRIPTION` file reflects the new version
- [ ] The `NEWS` file has been modified with the relevant information
- [ ] If necessary, changes were made to the WIKI to reflect new data, methodology, etc.

## Tests ran to verify the changes

<!-- For bug fixes and new features, describe the tests you ran to make sure everything works as expected, this can also help the reviewer make sure to run slightly different tests, or make sure that the same test generate the same results on a different set-up. -->

## Instructions for reviewer

> [!NOTE] General rules for developers
> - Reviewer should only be expected to review the code, not develop new tests, solutions or work on the code itself. If more work is needed, open targeted issues.
> - To make the review process easier, only make changes that pertain to the issue(s) at hand, avoid touching the rest of the codebase.
 
> [!NOTE] General rules for reviewers
> - We ask that reviewer don't change the codebase during review, but use the inline comments to suggests code changes when needed. 
> - Please avoid making comments on style preference, unless it has consequences on functions behaviour or ease of maintenance.

<!--
Describe here what is expected of the reviewer

- Level of review that is expected 
- If needed, path to data files or scripts to test the functions
- Area that need extra scrutiny
- What's NOT expected from the review (e.g. no need to comment on the code, just on functionalities)
--> 

## Time management

- Deadline:
- What clockify task should be used:
- Time budget: