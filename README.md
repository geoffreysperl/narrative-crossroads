# Narrative Crossroads

**A methodology for literary character analysis using tabletop roleplaying game mechanics**

---

## What is Narrative Crossroads?

Narrative Crossroads adapts the decision-making structures of tabletop roleplaying games (TTRPGs) to help students analyze literary characters from the inside out. Rather than observing characters from a critical distance, students step into pivotal moments—*crossroads*—where characters face meaningful choices, then use structured mechanics to explore motivation, consequence, and agency.

The method is grounded in three intersecting literacy frameworks:

- **Mechanical literacy** — Understanding rules and systems as interpretive lenses
- **Narrative literacy** — Engaging with story elements through active participation
- **Social literacy** — Navigating collaborative meaning-making

Narrative Crossroads is designed for secondary ELA classrooms and works particularly well with multilingual learners, who benefit from the scaffolded, low-risk environment that structured roleplay provides.

---

## Who Created This?

**Geoffrey Sperl** is an ELA/ESL teacher at Hamtramck High School in Michigan. He developed Narrative Crossroads as part of his MAT thesis, *The Effects of Playing Tabletop Roleplaying Games in the Classroom on the Academic Literacy of Secondary Students* (Wayne State University, 2025).

Geoffrey sponsors his school's TTRPG Club and presents on TTRPG pedagogy at conventions including ChaosiumCon.

- Website: [teaching.geoffreysperl.com](https://teaching.geoffreysperl.com)
- Contact: [geoffrey@geoffreysperl.com](mailto:geoffrey@geoffreysperl.com)

---

## Repository Structure

```
narrative-crossroads/
├── index.md                   # Homepage
├── quickstart.md              # The no-dice entry version — one class period
├── workshop.md                # Follow-up for Quest-Based Learning attendees
├── downloads.md               # Index of printable materials
├── acknowledgments.md
│
├── method/                    # Core methodology documentation
│   ├── overview.md            # How Narrative Crossroads works
│   ├── why-it-works.md        # Research evidence and cognitive mechanisms
│   ├── theoretical-foundations.md
│   ├── gaming-literacy-model.md
│   └── ml-scaffolding.md      # Adaptations for multilingual learners
│
├── practice/                  # Implementation resources
│   ├── implementation-guide.md
│   ├── character-analysis-tools.md
│   ├── standards-alignment.md # Michigan ELA standards mapping
│   └── modules/               # Text-specific applications
│
├── research/                  # Scholarly foundation
│   ├── annotated-bibliography.md
│   └── research-gaps.md
│
├── resources/                 # External links and tools
│   └── links.md
│
├── downloads/                 # Printable PDFs served by the site
│
├── presentations/             # Conference and PD materials
│   ├── chaosiumcon-2025/
│   ├── chaosiumcon-2026/
│   └── hamtramck-pd-2026/
│
└── _sass/                     # Theme customization
    ├── color_schemes/custom.scss
    └── custom/custom.scss     # Print styles
```

---

## Getting Started

**For teachers:**
Start with [quickstart.md](quickstart.md) — one class period, no dice, no game. Then [method/overview.md](method/overview.md) for the conceptual grounding and [practice/implementation-guide.md](practice/implementation-guide.md) for classroom logistics.

**For researchers:**
The [research/](research/) folder contains the scholarly foundation, including an annotated bibliography and identified gaps in the current literature.

**For game designers:**
The [method/gaming-literacy-model.md](method/gaming-literacy-model.md) explains how TTRPG mechanics map to literacy objectives—useful if you're designing educational games.

---

## Local Development

The site is built by GitHub Pages. To run it locally with the same Jekyll
version GitHub uses:

```
bundle install
bin/serve
```

Then open <http://127.0.0.1:4000>.

`Gemfile` pins the `github-pages` gem, so a local build matches the deployed
one. `github-pages` requires Ruby >= 2.7; macOS ships 2.6, and `bin/serve`
will reach for a Homebrew Ruby if the default is too old.

The Just the Docs theme is pinned by version in `_config.yml`. Unpinned, it
tracks the theme's default branch and can change without a commit here.

---

## Related Resources

- [TabletopEDU](https://www.tabletopEDU.org) — Nonprofit organization advancing TTRPGs in education
- [Adventures in Learning & Teaching](https://www.tabletopEDU.org) — Practitioner guide by Garrett Munro and Maryanne Cullinan, PhD

---

## License

This work is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). You are free to share and adapt this material with attribution.

---

## Changelog

See [CHANGELOG.md](CHANGELOG.md) for version history.
