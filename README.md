# Open Y Project On Pantheon

This experimental repository exists to blend the Open Y Project repo and Pantheon's example-drops-8-composer repository which demonstrates a GitHub -> CircleCI -> Pantheon workflow.

Copies of this repo can be generated with a variation of the one command setup used for example-drops-8-composer.

First add tokens for GitHub and CircleCI:

```
export GITHUB_TOKEN=[REDACTED]
export CIRCLE_TOKEN=[REDACTED]
```

Then run this command from the Build Tools Plugin for Pantheon's Terminus command line tool.

```
terminus build:project:create stevector/openy-project-on-pantheon/ openy-site-machine-name --team="My Pantheon Org"
```
