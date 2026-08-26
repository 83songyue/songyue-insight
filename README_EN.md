# Songyue Consumer Insight Skill

<p align="center">
  <img src="assets/songyue-avatar.png" alt="Songyue" width="140">
</p>

[中文](README.md)

`songyue-insight` helps an AI agent investigate consumer behavior and explain what lies behind it. Start with an incomplete brief, a product category, an audience, or a proposed insight.

Its focus is **observation → explanation → insight**: enough evidence and reasoning to understand the judgment, followed by plain, precise language. It does not turn every research request into a marketing strategy.

This skill shares the practical, evidence-oriented approach of Songyue's marketing diagnosis work, but serves a different purpose: understanding consumer choices before developing a strategy. It works independently of other repositories.

## Usage

After installation, ask your agent:

```text
Use songyue-insight to investigate consumer insights for a fresh-snack brand.
```

```text
Use songyue-insight to explore consumer insights about word-of-mouth for an insurance brand.
```

```text
Is this statement a consumer insight, an observation, or just copywriting?
```

In hosts supporting dollar-prefixed skill invocation, use `$songyue-insight`. Instructions are Chinese-first; you can request English output.

## What to expect

- At least two distinct, supported insights for open-ended research when the evidence permits; three or four are welcome. Never invent findings to meet a quota.
- Concrete behavior or consumer accounts, readable source links, a short explanation, and a concise insight for each finding.
- Explicit boundaries and tentative labels where needed.
- An optional separate observation for a narrower segment or situation.
- No default strategy report. Direct implications, if useful, stay brief.

Research routes depend on the audience, decision-making role, consumption stage, and evidence needed. Posts, comments, purchase decisions, alternatives, complaints, and credible reports serve different roles. Company-selected testimonials are not treated as independent consumer research.

## Install

Download the repository ZIP or clone it:

```bash
git clone https://github.com/83songyue/songyue-insight.git
```

Import the complete **`songyue-insight/` subfolder** into an Agent Skills-compatible host. Keep its references, metadata, license, and notice. The repository root is not the skill folder. Back up or confirm an update before replacing an existing installation.

This repository is a skill package, not a hosted application. It includes no model account, search service, or platform credentials. Research requires the host's available, authorized browsing tools or user-provided materials. If a platform is inaccessible, the agent should say so, seek comparable sources, and narrow its conclusions.

## About the author

Songyue (宋玥) is a brand marketing and creative strategy practitioner with 20 years of hands-on experience, including roles as:

- Creative Director at Ogilvy
- Marketing Creative Lead for a Business Group at Tencent
- Founding Partner of Beijing Tianyukong (天与空)

His work spans brand, advertising, content, and business growth projects across internet services, fast-moving consumer goods, emerging consumer brands, and food and beverages.

To learn more or contact Songyue, visit [songyue.me](https://songyue.me).

## Included resources

- `SKILL.md`: workflow, evidence boundaries, and delivery standards.
- `references/source-routing.md`: source selection and counter-evidence.
- `references/quality-gates.md`: distinguish insights from observations and slogans.
- `references/case-calibration.md`: anonymized reasoning examples, hypotheses, and counterexamples.
- `agents/openai.yaml`: host-facing metadata.
- `LICENSE` and `NOTICE`: attribution and reuse conditions, retained with the installable folder.

No raw client proposals, private briefs, training documents, personal source paths, or credentials are included. Calibration examples are not evidence about the category currently being researched.

## License

Copyright © 2026 Songyue / 宋玥.

Licensed under **CC BY-NC-SA 4.0**, matching the author's existing marketing diagnosis project. Non-commercial sharing and adaptation are permitted under the license's attribution and share-alike conditions. Commercial use requires separate written permission.

See [LICENSE](LICENSE), [NOTICE](NOTICE), and the [Creative Commons summary](https://creativecommons.org/licenses/by-nc-sa/4.0/). Public availability does not imply unrestricted commercial use or endorsement rights to the author's name and branding.
