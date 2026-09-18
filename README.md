# Music Computing Research

An [Obsidian](https://obsidian.md) vault mapping the music computing / audio
technology landscape — the academic labs, companies, researchers, concepts,
and unsolved problems that make up the field — with an eye toward spotting
where a real product could be built.

Notes are linked together throughout (`[[wikilinks]]`), so the vault is meant
to be browsed in Obsidian rather than read file-by-file. It uses the
[Dataview](https://github.com/blacksmithgu/obsidian-dataview) community
plugin (bundled under `.obsidian/plugins/`) to generate live tracker tables
from note frontmatter.

## Structure

**By country** — `Austria/`, `Belgium/`, `Canada/`, `Denmark/`, `Finland/`,
`France/`, `Germany/`, `Italy/`, `Netherlands/`, `Norway/`, `Singapore/`,
`Spain/`, `Sweden/`, `UK/`, `USA/`
Each country folder holds `Labs/` and `Companies/`, one subfolder per
organization. An org folder contains a `Lab.md` or `Company.md` overview
(frontmatter: `org`, `org_type`, `country`, `status`, `resources_count`,
`researchers_count`, `date_last_updated`), plus `Researchers/` (one note per
person: role, affiliation, LinkedIn/email if found) and `Resources/` (papers,
patents, articles, products tied to that org).

**`Concepts/`** — ~135 notes, one per research area or technique (e.g.
`Ambisonics.md`, `AI Music Generation.md`, `Physical Modeling Synthesis.md`).
Each is a short explainer with a "Seen in" section linking every resource
across every country/org where that concept shows up.

**`Pain Points/`** — Concrete, named unsolved problems in the field (e.g.
*"Generic HRTFs Cause Poor Sound Localization, but Individualized HRTFs Are
Too Expensive to Measure at Scale"*), each surfaced from and linked back to
a Concept, with metadata on whether it's been addressed and when it was
first identified.

**`Products/`** — Product-idea brainstorms per Concept (`<Concept> — Product
Ideas.md`), tracking build effort, distribution channel, and incumbency
risk for each idea.

**`Niche Shortlist/`** — Dated, ranked assessments (per Concept) of which
Pain Points are worth pursuing as a product, gated on factors like
commercial/research incumbency and whether the barrier is technical,
regulatory, awareness, or timing. Reasoning is spelled out per item; these
are inputs to a human go/no-go decision, not a recommendation to build.

**`Influencers/`** — Per-concept notes on key voices/accounts to follow.

**Top-level tracker notes** — `Coverage Tracker.md`, `Concepts Coverage.md`,
`Pain Points.md`, `Products.md`, `Influencers.md` are Dataview query notes
that render live summary tables over the folders above (they contain no
content of their own, just queries).

## Usage

Open the folder as a vault in Obsidian. The Dataview plugin is already
enabled (`.obsidian/plugins/dataview/`), so the tracker notes should render
their tables automatically.
