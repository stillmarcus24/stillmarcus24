## Marcus Still

Security engineer and researcher. I find and responsibly disclose
vulnerabilities, and I build the tooling that finds them at scale.

### What I am known for
- Coordinated-disclosure of multiple CWE-22 arbitrary-file-write
  vulnerabilities across the Model Context Protocol (MCP) server ecosystem,
  each source-confirmed and CodeQL-corroborated.
- The MCP CodeQL query pack - the taint queries GitHub's own CodeQL does
  not ship. Stock CodeQL models Express and Axios but not MCP, so it reports
  zero on a genuinely vulnerable MCP server; my source model fixes that and
  finds the real flows.
- A reusable GitHub Action that runs that scan in any MCP repo's CI.
- Contributions to the GitHub Advisory Database (including a mapping for a
  package at 25M+ weekly downloads) and a security-guidance issue on the
  official MCP TypeScript SDK.

### The work
[mcp-security-research](https://github.com/stillmarcus24/mcp-security-research)
- method, the CodeQL pack, the GitHub Action, an ecosystem security
  scorecard built from a 65,000-server census, and a named vulnerability
  class. Findings under coordinated disclosure; no unfixed package named.

### How I work
Measure before asserting. Source-confirm every finding against the
published artifact, not the analyzer output. Prove it, then ship it.
Responsible disclosure first - private report, coordinated window, public
advisory only after a fix.

Reach me: stillmarcus24@gmail.com
