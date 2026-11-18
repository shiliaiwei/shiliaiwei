<div align="center">

[![GitHub Streak](https://github-readme-streak-stats-eight.vercel.app?user=shiliaiwei&theme=neon&hide_border=true)](https://git.io/streak-stats)

</div>

## Chess.com profile state

[![Chess.com profile](https://img.shields.io/badge/Chess.com-visrie-769656?logo=chessdotcom&logoColor=white)](https://api.chess.com/pub/player/visrie)

<!-- chess-profile:start -->
### visrie

<table>
<tr><td><strong>Status</strong></td><td>premium</td></tr>
<tr><td><strong>Joined</strong></td><td>2025-06-07</td></tr>
<tr><td><strong>Last online</strong></td><td>2026-11-18</td></tr>
<tr><td><strong>Followers</strong></td><td>4</td></tr>
<tr><td><strong>League</strong></td><td>Champion</td></tr>
<tr><td><strong>Country</strong></td><td><a href="https://api.chess.com/pub/country/KH">Chess.com profile</a></td></tr>
</table>

[Open the live visrie profile](https://www.chess.com/member/visrie) · Updated 2026-11-18 11:35 UTC
<!-- chess-profile:end -->

## GitHub Metrics

```yaml
name: Example
uses: lowlighter/metrics@latest
with:
  filename: metrics.classic.svg
  token: ${{ secrets.METRICS_TOKEN }}
  base: header, repositories
  plugin_lines: yes
```

```yaml
name: 📗 Classic template
description: |
  A template mimicking GitHub visual identity.
  This is also the default template.
examples:
  default: https://github.com/lowlighter/metrics/blob/examples/metrics.classic.svg
index: 0
supports:
  - user
  - organization
formats:
  - svg
  - png
  - jpeg
  - json
```

```yaml
name: 🎟️ Follow-up of issues and pull requests
category: github
description: |
  This plugin displays the ratio of open/closed issues and the ratio of open/merged pull requests across repositories.
examples:
  +indepth analysis: https://github.com/lowlighter/metrics/blob/examples/metrics.plugin.followup.indepth.svg
  created on a user's repositories: https://github.com/lowlighter/metrics/blob/examples/metrics.plugin.followup.svg
  created by a user: https://github.com/lowlighter/metrics/blob/examples/metrics.plugin.followup.user.svg
index: 9
supports:
  - user
  - organization
  - repository
scopes:
  - public_access
inputs:

  plugin_followup:
    description: |
      Enable followup plugin
    type: boolean
    default: no

  plugin_followup_sections:
    description: |
      Displayed sections

      - `repositories`: overall status of issues and pull requests on your repositories
      - `user`: overall status of issues and pull requests you have created on GitHub
    type: array
    format: comma-separated
    default: repositories
    values:
      - repositories
      - user

  plugin_followup_indepth:
    description: |
      Indepth analysis
    type: boolean
    default: no
    extras:
      - metrics.api.github.overuse

  plugin_followup_archived:
    description: |
      Include archived repositories
    type: boolean
    default: yes
```
