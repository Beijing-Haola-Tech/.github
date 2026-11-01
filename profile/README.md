# Beijing Haola Tech · 好啦科技

AI-native health checkup services — 把体检能力做成 Agent 可以直接调用的接口。

## What we build

- **Haola Checkup MCP** — a Streamable HTTP MCP server exposing 25 checkup tools
  (store lookup, personalized plan recommendation, booking, rescheduling, report queries).
  Endpoint: `https://ai.ihaola.com.cn/api/mcp/haola-pe`
- **Agent Skills** — two published skills on ClawHub, one for personal checkup booking and
  one for corporate checkup quoting. Both bundle a zero-dependency Python client, so they
  also work in agents that do not support MCP OAuth.

## Coverage

240+ cities, 540+ bookable checkup centers across China.

## Links

- Website: https://www.ihaola.com.cn
- Source: https://github.com/Beijing-Haola-Tech/haola-checkup-mcp
- Skills on ClawHub:
  - [personal-checkup-booking](https://clawhub.ai/ryanbihai/skills/personal-checkup-booking)
  - [corporate-checkup-quote](https://clawhub.ai/ryanbihai/skills/corporate-checkup-quote)

## Contact

For partnership or enterprise checkup programs, open an issue in
[haola-checkup-mcp](https://github.com/Beijing-Haola-Tech/haola-checkup-mcp/issues).