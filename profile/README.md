<a href="https://vallkey.com">
  <img src="https://raw.githubusercontent.com/vallkeyhq/.github/main/assets/github-profile-banner-1280x320.png" alt="Vallkey — API keys with rules and a kill switch" width="1280" />
</a>

<p align="center">
  <a href="https://vallkey.com">Website</a> ·
  <a href="https://vallkey.com/docs/">Documentation</a> ·
  <a href="https://vallkey.com/integrations/">Integrations</a> ·
  <a href="https://vallkey.com/security/">Security</a>
</p>

### Give your API keys boundaries

Vallkey gives your applications **ghost keys**: stand-in credentials with permissions, limits, and a kill switch. Your app sends requests through Vallkey, which checks your rules before forwarding an allowed request to the provider with the real credential.

- **Control access.** Choose the methods and endpoints each ghost key can use.
- **Set limits.** Apply request limits, expiration dates, and AI usage budgets.
- **See what happened.** Review allowed and blocked requests, then revoke a ghost key when needed.

### Get started

Create an account at [vallkey.com](https://vallkey.com), then run these commands in your project:

```sh
npx vallkey@latest login
npx vallkey@latest init --dry-run
```

Review the detected credentials and proposed changes, then follow the [quick-start guide](https://vallkey.com/docs/quick-start/) to connect your application and verify its first request through Vallkey.

### Developer tools

| Tool | Use it to |
| --- | --- |
| [Command-line tools](https://vallkey.com/docs/cli/) | Configure connections and manage ghost keys from your terminal. |
| [GitHub Action](https://github.com/vallkeyhq/scan-action) | Scan code for exposed API keys in CI, with masked findings. |
| [MCP for coding agents](https://vallkey.com/docs/mcp/) | Connect your coding agent to Vallkey's key-management tools. |

Questions? [Contact the team](https://vallkey.com/contact/). Found a vulnerability? [Send a private security report](https://vallkey.com/contact/?topic=security).

---

[X / @vallkeyhq](https://x.com/vallkeyhq) · [LinkedIn](https://www.linkedin.com/company/vallkey) · [Service status](https://vallkey.com/status/)
