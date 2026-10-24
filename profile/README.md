# Hoffman Lenses Initiative

### Making the invisible visible.

The **Hoffman Lenses Initiative** is an independent, non-partisan, non-commercial project researching how online systems influence attention, behaviour, and public understanding—and developing tools to help people recognize manipulative techniques for themselves.

**Website:** [hoffmanlenses.org](https://hoffmanlenses.org) · **Research and software:** [GitHub repositories](https://github.com/orgs/HoffmanLensesInitiative/repositories)

> **Our approach:** Show the evidence. Explain the technique. Let people decide what it means. Hoffman is not a censorship tool: its purpose is to make potentially manipulative mechanisms visible, not to decide which opinions people may encounter.

## Why the initiative exists

Online feeds are not neutral lists of information. Ranking, recommendation, promotion, and interface design can influence what people encounter and how they respond. The initiative calls systems designed or optimized to exploit psychological vulnerabilities **Behavioral Manipulation Systems (BMS)**.

The project investigates the incentives, design choices, and possible harms associated with these systems. Its research and advocacy seek greater transparency, accountability, and user agency, with particular concern for young people and families affected by online harms.

Identifying a persuasive or emotionally charged passage does **not**, by itself, establish intent, unlawful conduct, causation, or harm. Findings must be interpreted in context and supported with evidence. The initiative's policy arguments are advocacy positions, not settled scientific or legal conclusions.

The name draws inspiration from the revealing glasses in John Carpenter's 1988 film *They Live*.

## What we're building

### Hoffman Browser — primary software direction

A desktop browser research instrument built with **Electron/Chromium**. The browser project is designed to analyze rendered page text and explain potentially manipulative language patterns, with local-model analysis as a core approach.

Examples of patterns the project explores include artificial urgency, outrage engineering, false authority, group-identity pressure, and attention-capturing hooks. The user remains responsible for evaluating whether a flag is meaningful.

**Project:** [hoffman-core / hoffman-browser](https://github.com/HoffmanLensesInitiative/hoffman-core/tree/main/hoffman-browser)

The repository contains prototype components; it should not be taken as certification of detection accuracy or readiness for everyday or forensic use. Exact privacy behaviour and model requirements depend on configuration and should be verified in the current application.

### Behavioral Manipulation Intelligence Database (BMID)

BMID is an evidence-oriented research system for documenting actors, techniques, incentives, distribution paths, and alleged or documented outcomes. Its research vocabulary includes **fisherman**, **bait**, **hook**, **net**, **catch**, **motive**, and **evidence**.

The [BMID API](https://github.com/HoffmanLensesInitiative/hoffman-core/tree/main/bmid-api) provides a Python/Flask implementation and underlying data model. Database records are research materials, not automatic findings of legal liability.

### hl-detect — standalone analysis library

[hl-detect](https://github.com/HoffmanLensesInitiative/hoffman-core/tree/main/hl-detect) is a JavaScript library for identifying predefined linguistic patterns in supplied text. It is platform-independent and separate from the primary Hoffman Browser model-analysis path.

Its flags are heuristics, not a substitute for context-sensitive human assessment.

### Earlier browser extension

The [Hoffman Lenses extension](https://github.com/HoffmanLensesInitiative/hoffman-lenses-extension) explored browser-side annotation, initially oriented toward Facebook and Firefox. The project's master build document records that **extension development was halted in March 2026** in favour of the standalone browser. The repository remains available as an earlier implementation and reference.

### Website, resources, and education

[hoffmanlenses.org](https://hoffmanlenses.org) hosts the initiative's public-facing resources. The [website repository](https://github.com/HoffmanLensesInitiative/hoffman-lenses-website) contains information pages, white-paper materials, family-focused content, and remembrance resources.

The core repository also contains research reports and educational course drafts. These materials vary in maturity: a draft, research note, or proposed outreach does not establish publication, external endorsement, or completed contact.

## Our principles

- **Transparency over censorship.** Explain techniques and evidence without hiding or removing user-selected content.
- **User agency.** Provide context so people can make their own judgements.
- **Evidence before accusation.** Distinguish sourced observations, interpretations, allegations, and legal findings.
- **Political neutrality in analysis.** Evaluate methods rather than flagging content solely because of viewpoint.
- **Privacy by design.** Favour on-device processing and minimize collection; review actual data flows for each component.
- **Care with vulnerable people and families.** Avoid sensationalism, presuming consent, or speaking for affected people.
- **Open methods and scrutiny.** Make assumptions, limitations, and software accessible for examination where possible.

## Explore the repositories

| Repository | Contents |
| --- | --- |
| [hoffman-core](https://github.com/HoffmanLensesInitiative/hoffman-core) | Main monorepo: browser, BMID API, hl-detect, reports, course drafts, and agent workflows |
| [hoffman-lenses-extension](https://github.com/HoffmanLensesInitiative/hoffman-lenses-extension) | Earlier browser-extension prototype, no longer the primary development path |
| [hoffman-lenses-website](https://github.com/HoffmanLensesInitiative/hoffman-lenses-website) | Public website source and resources |

For detailed project direction, see [HOFFMAN.md](https://github.com/HoffmanLensesInitiative/hoffman-core/blob/main/HOFFMAN.md). Some recorded status claims date from March–April 2026 and should be checked against current code and releases.

## Who this is for

Researchers, journalists, educators, parents, advocates, technologists, legal professionals, and readers who want to understand mechanisms shaping the information they encounter.

The initial browser direction emphasizes a **research instrument**, not a claim to a finished consumer browser or a validated system for assessing individual posts.

## Contributing and responsible reporting

Careful examination of the public source and documented research is welcome. Useful contributions include reproducible bug reports, privacy and security reviews, accessibility improvements, false-positive and false-negative examples, better evaluation methods, and corrections supported by primary sources.

Open an issue in the relevant repository to discuss a proposed change. **Do not post private browsing histories, children's personal information, confidential case material, or private account credentials in public GitHub issues.** Automated detections are not proof against named individuals or organizations.

Contribution terms and licensing may differ among repositories and between code and written works; consult each project's actual license files before reuse.

## Status and limitations

The initiative is a collection of research materials and software prototypes, not a certified browser-safety product, medical intervention, legal service, or authoritative fact-checker. AI and rule-based classifications may be wrong or incomplete. Available code does not establish that every proposed feature is deployed, tested, or suitable for sensitive investigations.

For published material and updates, start at [hoffmanlenses.org](https://hoffmanlenses.org).

---

*The aim is awareness, accountability, and informed choice.*
