Changelog
=========

This is a simple changelog over notable milestones for the [NAIS-platform](/documentation/platform.md).


## [Unreleased]
- We are rewitting Naisd to be a third-party app for Kubernetes, using the Kubernetes Operator toolset. Check out the [naiserator](https://github.com/nais/naiserator) repo for more info. It is possible to start using this now
- Vault is missing in SBS-zone


## [Released]
### [2018-10-26]
- Changed security model from everyone has read/write to read everyting and write only on team-specific resources. See [slack-message](https://nav-it.slack.com/archives/C5KUST8N6/p1540292509000100) for what to do

### [2018-09-24]
- Added Vault by Hashicorp, which is a tool to manage secrets, see [documentation](/documentation/contracts/vault.md) for more

### [2018 - June]
- Created a new service/bot for Slack, to help team arrange stand-up. Check out [standup.nais.io](https://standup.nais.io/)

### [2018 - March]
- Added Redis operator to the platform, see [documentation](/documentation/services/redis.md) for more

### [2018 - February]
- Added option for leader election, see [documentation](/documentation/services/leader_election.md) for more

### [2018 - January]
- New service for creating ForgeRock [AM config](contracts/am.md) (Norwegian) in SBS or FSS, it's called Named (NAIS Access Management Extension)
