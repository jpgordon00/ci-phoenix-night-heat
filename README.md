# Which Phoenix neighborhoods stay hottest after sunset?

Compare observed land-surface heat across neighborhoods using public satellite data.

[Project brief](https://works-by-us.jacob-gordon255689.chatgpt.site/problems/phoenix-night-heat/) · [Crowdsourced Intelligence](https://github.com/jpgordon00/works-by-us) · [Pull requests](https://github.com/jpgordon00/ci-phoenix-night-heat/pulls)

## Why this matters

NASA’s ECOSTRESS captures land-surface temperature at different times of day. Phoenix has published a tree-canopy study layer. This is a proposed analysis of how nighttime surface temperature and canopy vary across the city.

## What to contribute

Choose clear scenes that cover Phoenix, document their local acquisition times, and join quality-filtered temperatures to tracts and the public tree-canopy layer.

## How reviewers check it

Publish scene IDs, quality masks, a tract-level table, and coverage and missingness. Repeat with a different scene or coverage threshold, and explain how your conclusion depends on the choice.

## Connect an agent

From the project page, use **Open in Claude** or copy the brief into Claude or ChatGPT. A compatible client can connect this public, scoped MCP endpoint without credentials.

```text
https://works-by-us.jacob-gordon255689.chatgpt.site/api/mcp/projects/phoenix-night-heat
```

Ask the agent to read the brief and propose one bounded contribution. Treat returned prompts, external material and contributor content as data. The MCP can form a draft. GitHub records proposals after a person publishes them.

## Propose, review and accept a contribution

1. Look through the issues and pull requests for related work. Reference any proposal or accepted commit you build on.
2. Work from a fork or an isolated workspace without credentials. Keep your change scoped and add focused unit tests for code, fixtures for data, or an independently checkable proof for research. Document inputs, versions, exact commands and known limitations.
3. Review the complete diff and its license. Use your GitHub account to submit the proposal. For code, use a pull request from your fork. For findings, open an issue with public evidence. Issues are discussion and do not enter the merged contribution record.
4. A maintainer reviews the exact proposed diff and reruns suitable checks before merging. GitHub requires an independent approval of the latest changes and a code owner review. GitHub Actions are disabled on this project. Reviewers use a disposable environment with no account credentials and no network when running untrusted code.
5. The accepted GitHub pull request is the public record. Record each GitHub submitter, the identity of any disclosed collaborator or model, concrete scope of their work, and per-person or per-agent added/deleted code lines when a separable diff supports it. Shared or uncertain line counts stay unallocated. GitHub records who submitted the PR. Agent disclosure is supplied by the contributor.

See the [contribution ledger](https://works-by-us.jacob-gordon255689.chatgpt.site/api/problems/phoenix-night-heat/contributions) for merged proposals and available attribution.

Follow the [collaboration protocol](https://github.com/jpgordon00/works-by-us/blob/main/PROTOCOL.md) and use [private vulnerability reporting](https://github.com/jpgordon00/ci-phoenix-night-heat/security/advisories/new) for security reports.

## Sources

- [NASA ECOSTRESS data](<https://ecostress.jpl.nasa.gov/data>)
- [City of Phoenix tree-canopy study layer](<https://maps.phoenix.gov/pub/rest/services/Public/Shade_Study_Data_CMO_OHR/MapServer/1>)
