<p align="center">
  <img src="https://geeduzbsatvodnlijqfs.supabase.co/storage/v1/object/public/product-media/c059e319-ea19-4aff-9b6c-39797f90a2b4/cb86581a-07b8-4ef2-be2a-6cb2b59062ae/logo-1795644327387-0.webp" alt="AgencyDesk Title &amp; Escrow" width="180" height="180" />
</p>

# AgencyDesk Skills — Title & Escrow (Free Sample)

[![skills.sh](https://skills.sh/b/LandrewConsulting/agencydesk-skills-title-escrow)](https://skills.sh/LandrewConsulting/agencydesk-skills-title-escrow)
[![Get the full Title & Escrow pack](https://img.shields.io/badge/AgencyDesk_Skills-Get_the_full_Title_%26_Escrow_pack-28aaaa)](https://landmconsultinginc.com/ai-skills/)
[![Agensi Listing](https://img.shields.io/badge/Agensi-Closing_Disclosure_Settlement_Comparison-0c182c)](https://agensi.io/skills/closing-disclosure-settlement-comparison)
[![License: MIT](https://img.shields.io/badge/License-MIT-e8a83c)](./LICENSE)

Clerical AI agent skills by **AgencyDesk Skills** (L&M Consulting Inc.). This repository hosts a single free sample from the 10-skill AgencyDesk Title & Escrow pack: **`closing-disclosure-settlement-comparison` (Closing Disclosure Settlement Comparison)** (public free-sample distribution accepted).

Skills follow the open [Agent Skills](https://agentskills.io/) specification. Explore all AgencyDesk skill packs at the [AgencyDesk Skills Store](https://landmconsultinginc.com/ai-skills/).

## Available Skill

### `closing-disclosure-settlement-comparison` — Closing Disclosure Settlement Comparison

Compares figures between a Closing Disclosure (CD) and a settlement statement and outputs a structured clerical review draft:

- **Line-by-line cited comparison:** extracts corresponding figures exactly as printed with document, page, and section citations on both sides.
- **Defined clerical statuses:** uses only `Documented match`, `Documented difference`, `Verification required`, `Not found in supplied documents`, and `Unclear — unreadable or ambiguous`, labeling single-sided items as `Not listed on [named source]`.
- **Title-premium caution:** flags title premium, simultaneous-issue, and seller-CD items as `Verification required` rather than calling a presentation difference an error.
- **Strict NPI masking:** masks Social Security numbers, account/routing numbers, loan numbers, and other nonpublic personal information as `[on file]`.

## Installation

Install with the [skills CLI](https://skills.sh/docs/cli):

```bash
npx skills add LandrewConsulting/agencydesk-skills-title-escrow
```

Or target a specific agent (for example Claude Code or Cursor):

```bash
npx skills add LandrewConsulting/agencydesk-skills-title-escrow --skill closing-disclosure-settlement-comparison -a claude-code
```

> [!TIP]
> This is a free sample from AgencyDesk Skills. Get the full Title & Escrow bundle and more skills for small businesses and industries at the [AgencyDesk Skills Store](https://landmconsultinginc.com/ai-skills/).

## Example Prompt

```text
Compare the attached Closing Disclosure against the settlement statement. List documented matches, documented differences, and any title-premium items requiring qualified review, with page and section citations.
```

## What This Skill Does NOT Do (Clerical Only)

This skill is strictly a clerical document-comparison tool for internal agency use under qualified settlement review:

- Does **not** call any difference an error, state that a figure is correct or compliant, or declare that funds are good or a file is ready to close or fund.
- Does **not** opine on TRID timing, three-day waiting period restarts, simultaneous-issue title premium disclosure rules, seller CD timing, or fee tolerances.
- Does **not** provide title opinions, legal advice, coverage determinations, or compliance determinations, and does **not** explain or counsel borrowers on loan terms.
- Does **not** send, file, record, contact any party, or take any outside action, and must **not** be used as a borrower-, buyer-, or seller-facing chatbot.
- Every output begins with `Internal use only — Draft for qualified review` and ends with the full clerical disclaimer requiring review by a qualified title officer, escrow officer, attorney, or licensed settlement professional.

## Supported Agents

Compatible with AI agents that support the [Agent Skills](https://agentskills.io/) specification, including **Claude Code**, **Cursor**, **Codex**, **OpenCode**, **Windsurf**, **Cline**, **GitHub Copilot**, **Gemini CLI**, **Roo Code**, and [70+ others](https://github.com/vercel-labs/skills/blob/main/docs/agents.md).

## Skill Structure

```text
skills.sh.json
skills/
  closing-disclosure-settlement-comparison/
    SKILL.md
    references/
      glossary.md
```

## Links

- **AgencyDesk Skills Store (full packs & more):** [https://landmconsultinginc.com/ai-skills/](https://landmconsultinginc.com/ai-skills/)
- **Agensi Listing (`Closing Disclosure Settlement Comparison`):** [https://agensi.io/skills/closing-disclosure-settlement-comparison](https://agensi.io/skills/closing-disclosure-settlement-comparison)

## License

This repository is licensed under the [MIT License](./LICENSE). Skills are provided "as is" without warranty; outputs are clerical drafts only and require review by a qualified title officer, escrow officer, attorney, or licensed settlement professional before reliance or external use.

---

### More AgencyDesk Skills

Looking for the full Title & Escrow pack or more skills for small businesses and industries? Explore all packs at **[landmconsultinginc.com/ai-skills](https://landmconsultinginc.com/ai-skills/)**.

Published by L&M Consulting.
