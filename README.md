## Marcus Still — Still OS Digital Holdings LLC

Independent security research and trust infrastructure for the autonomous agent economy.

**Security research (public, third-party-verified):**
- **CVE-2026-106763** — RCE in `@justice8096/sagemath-mcp-server`
- **CVE-2026-106764** — RCE in `@rog0x/mcp-git-tools`
- **CVE-2026-106765** — RCE in `@rog0x/mcp-docker-tools`

All three are command-injection → remote code execution in published MCP (Model Context Protocol) servers, reported through MITRE and credited to Still OS Digital Holdings LLC.

**Standards work:**
- Authoring the **correctness & dispute extension** for the x402 payment standard ([x402-foundation/x402#3868](https://github.com/x402-foundation/x402/pull/3868)) — the layer that adjudicates whether what was paid for was *correct*, backed by an on-chain bond.

**What I build:** a correctness/dispute & trust layer for machine-to-machine commerce — signed, hash-chained verdicts; an on-chain, independently-checkable correctness bond; and zero-dependency conformance kits so anyone can verify the work without trusting me.

- Reference kit: [notary-x402-reference-kit](https://github.com/stillmarcus24/notary-x402-reference-kit)
- Independent verifiers: [stillos-kyaos-verifier](https://github.com/stillmarcus24/stillos-kyaos-verifier) · [stillos-ai-provenance](https://github.com/stillmarcus24/stillos-ai-provenance)

Everything I publish is designed to be recomputed by a stranger. Verify, don't trust.
