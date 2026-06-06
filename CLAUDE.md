# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What This Repository Is

A structured investment knowledge base extracted from 73 SOIC (School of Intrinsic Compounding) webinar PDFs. It contains frameworks, metrics, checklists, and sector analysis for Indian equity investing. There is no code — all content is in markdown files.

## Navigation

Always start with `00_INDEX.md`. It contains:
- A quick-lookup table mapping topics to file numbers
- Section-by-section summaries of what each file covers
- A valuation-by-sector reference table
- Universal red flags and key thresholds

## File Architecture

Files are numbered by topic domain, not dependency order:

| Range | Domain |
|-------|--------|
| `01–02` | Financial statement analysis and ratios |
| `03` | Valuation frameworks |
| `04` | Sell decisions and probabilistic thinking |
| `05` | Moats and competitive advantage |
| `06` | Buy frameworks and entry timing |
| `07` | Investing checklist, forensics, research tools |
| `08` | Banking, NBFCs, Insurance |
| `09` | Capital allocation and value chain analysis |
| `10` | Chemicals, pharma, agrochemicals, CDMO |
| `11` | Healthcare, biotech, hospitals |
| `12` | Energy, oil & gas, metals, mining |
| `13` | Industrials, defense, shipping, aerospace, next-leg framework |
| `14` | Consumer sectors, SaaS, sector rotation |

## Answering Investment Questions

When asked about a specific company, sector, or concept:
1. Check `00_INDEX.md` quick navigation table first
2. Go to the relevant numbered file
3. The large files (`05`, `10`, `13`, `14`) contain multiple merged sub-topics — use markdown headings to navigate within them

For cross-cutting questions (e.g. "how to evaluate management quality"), check `07_checklists_forensics_tools.md` — it has the master checklist and red flags that apply across all sectors.

## Updating Content

When adding new content to an existing file, follow the existing heading hierarchy and bullet-point style — the files use a consistent pattern of `##` for major topics, `###` for sub-topics, and tables/bullets for data. After editing any file, update the relevant summary in `00_INDEX.md` to reflect the change.

When adding a new sector or topic that doesn't fit existing files, create a new numbered file following the range conventions above, and add it to the Quick Navigation table and a new section in `00_INDEX.md`.

## Key Content Locations

- **SOIC 16-step investing checklist**: `07_checklists_forensics_tools.md`
- **Sector-specific valuation metrics**: `00_INDEX.md` → "Valuation by Sector" table, and `03_valuation.md`
- **Good business thresholds** (ROCE, GNPA, NIM, etc.): `00_INDEX.md` → "Key Thresholds" table
- **Universal red flags**: `00_INDEX.md` → "Red Flags" table, and `07_checklists_forensics_tools.md`
- **Company examples**: scattered throughout sector files; `05_moats.md` has the largest company reference table (40 companies with moat type)
- **When to sell**: `04_sell_and_decisions.md` — Stage Analysis framework + 12 probabilistic maxims
- **SOIC 5-Bucket Framework**: `10_chemicals_pharma.md` (applies across sectors)
