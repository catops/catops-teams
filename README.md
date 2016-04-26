# CatOps Teams [![Build Status](https://img.shields.io/travis/catops/catops-teams.svg?maxAge=2592000&style=flat-square)](https://travis-ci.org/catops/catops-teams.svg?branch=master) [![npm](https://img.shields.io/npm/v/catops-teams.svg?maxAge=2592000&style=flat-square)](https://www.npmjs.com/package/catops-teams)

:cat: Create and manage team members using Hubot. Based on [hubot-team](https://github.com/hubot-scripts/hubot-team).

## Installation

Add **catops-teams** to your `package.json` file:

```json
"dependencies": {
  ...
  "catops-teams": "latest"
}
```

Add **catops-teams** to your `external-scripts.json`:

```json
["catops-teams"]
```

Run `npm install catops-teams`


## Configuration

Some commands require an 'admin' role to be run (i.e. `clear` team list). The
admins can be specified through the `HUBOT_TEAM_ADMIN` environment variable,
as a comma separated list of usernames.


## Commands

```
hubot create team <team_name> - create team called <team_name>
hubot (delete|remove) team <team_name> - delete team called <team_name>
hubot (list|show) teams - list all existing teams
hubot add (me|<user>) to team <team_name> - add me or <user> to team
hubot remove (me|<user>) from team <team_name> - remove me or <user> from team
hubot (list|show) team <team_name> - list the people in the team
hubot (empty|clear) team <team_name> - clear everyone from team
```

----

## Open source licensing info
1. [TERMS](TERMS.md)
2. [LICENSE](LICENSE)
3. [CFPB Source Code Policy](https://github.com/cfpb/source-code-policy/)
