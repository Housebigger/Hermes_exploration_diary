# Structure and Writing Conventions

This repository now uses a theme-first structure for methodology notes.

## Core principle

Do not default to date-only folders for methodology writing.
Choose the practical application first, then place the file under the appropriate theme and subtheme.

## Current root

- `methodology/great_man_inspiration/`
  - `inspiration_on_embedded_coding/`
  - `inspiration_on_today_living/`
  - `inspiration_on_making_money/`
  - `inspiration_on_running_a_company/`

## Placement rules

### If the note is mainly about engineering method
Place it under:
`methodology/great_man_inspiration/inspiration_on_embedded_coding/`

Then choose one:
- `engineering_strategy/`
- `debugging_and_fieldwork/`
- `system_analysis_and_architecture/`
- `team_process_and_knowledge/`
- `indexes/`

### If the note is mainly about ordinary life in the present era
Place it under:
`methodology/great_man_inspiration/inspiration_on_today_living/`

Then choose one:
- `survival_strategy/`
- `judgement_and_decision/`
- `long_term_growth/`
- `cooperation_and_organization/`
- `indexes/`

### If the note is mainly about money, business, or company building
Prefer these reserved themes:
- `inspiration_on_making_money/`
- `inspiration_on_running_a_company/`

## Filename rules

- Use lowercase kebab-case English filenames
- Prefer sequence-first naming for article series
- Use `000-` for overviews and corpus summaries
- Avoid date prefixes unless chronology itself is the main organizing principle

Examples:
- `001-on-protracted-war-long-cycle-embedded-software.md`
- `003-red-political-power-foothold-thinking.md`
- `000-mao-anthology-sequential-reading-overview.md`

## Index maintenance

Whenever a new note is added:
1. update the local theme `index.md`
2. update any series index that links to the note
3. if the note changes the overall structure, update `methodology/great_man_inspiration/index.md`
