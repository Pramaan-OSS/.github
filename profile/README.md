<div align="center">

<img src="https://raw.githubusercontent.com/Pramaan-OSS/.github/main/profile/banner.svg" alt="Pramaan OSS: building blocks to launch your products and ideas to market, fast." width="100%">

<br>

**Open-source building blocks to launch your products and ideas to the market quickly.**

<br>

[![License: AGPL-3.0](https://img.shields.io/badge/license-AGPL--3.0-41a1cf?style=for-the-badge&labelColor=1f1f29)](https://github.com/Pramaan-OSS/.github/blob/main/LICENSE)
[![Open source](https://img.shields.io/badge/open%20source-always-41a1cf?style=for-the-badge&labelColor=1f1f29)](https://github.com/Pramaan-OSS)
[![PRs welcome](https://img.shields.io/badge/PRs-welcome-41a1cf?style=for-the-badge&labelColor=1f1f29)](https://github.com/Pramaan-OSS/.github/blob/main/CONTRIBUTING.md)

</div>

<br>

## Why Pramaan

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>One API</h3>
      Call a capability. We handle the providers, the keys and the glue, so you ship the product instead of the plumbing.
    </td>
    <td width="33%" valign="top">
      <h3>Best output, lowest cost</h3>
      Every call is routed to the provider that delivers the result at the lowest cost, and falls back automatically when one fails.
    </td>
    <td width="33%" valign="top">
      <h3>Open by default</h3>
      Read it, run it yourself, switch providers any time. No lock-in. Licensed AGPL-3.0.
    </td>
  </tr>
</table>

<br>

## How a call flows

```text
  your app / agent
        |
        v
   one capability call        e.g. search, page read, enrichment, email, auth, payments
        |
        v
   Pramaan routes it   --->   provider A     provider B     provider C
        |                          x (fails)     OK (lowest cost)
        v
   clean result               provider traces stripped
```

<br>

## Projects

Projects are added here as they are released. Each lives in its own repository.

| Project | What it is | Status |
| --- | --- | --- |
| _First release coming soon_ | The capabilities SDK: one API, many providers | In preparation |

<br>

## Get involved

- **Found a bug or have an idea?** Open an issue in the repo it belongs to.
- **Want to contribute?** Read [CONTRIBUTING](https://github.com/Pramaan-OSS/.github/blob/main/CONTRIBUTING.md) first. Small pull requests are the easiest to merge.
- **Found a security problem?** Follow [SECURITY](https://github.com/Pramaan-OSS/.github/blob/main/SECURITY.md). Please do not open a public issue.

<br>

<div align="center">

<sub>Pramaan means proof. Everything here is built in the open so you can check it.</sub>

</div>
