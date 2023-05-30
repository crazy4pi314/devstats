
1. Setup Authorization
2. Parse/pass click options
    a. fetch data
3. Generate report

# Issues

devstats -i org repo --state --since --tags --state

user: filter, state, labels, sort, direction, since, collab, orgs, owned, pulls
org: org, filter, state, labels, sort, direction, since, per_page, page
repo: owner, repo, milestone, state, assignee, creator, mentioned, labels, sort, direction, since, per_page, page

## required
owner
repo

## optional
state
labels
since
milestone

# PRs

devstats -pr org repo --state --since --tags
state, head, base, sort, direction, per_page, page

## required
owner
repo

## optional
state

