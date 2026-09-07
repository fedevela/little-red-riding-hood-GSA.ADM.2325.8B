# Little Red Riding Hood

A two-character theatrical adaptation for forum theatre. Red's journey meets the
Wolf's patient pursuit; the story gathers toward a danger whose outcome remains
unresolved. The [story bible](bible/README.md) establishes the characters, world,
and dramatic foundations. Season 1 is the current writing assignment.

## Project Layout

- `bible/`: project, cast, world rules, themes, dramatic arcs, and relationships.
- `bible/characters/little_red_riding_hood/` and `bible/characters/wolf/`: the two
  complete profiles, each with appearance, personality, interior voice, wants,
  fears, secrets, and lexicon files.
- `Script/Season_01/Episode_01/Scene_01/Beat_01/`: the existing writing hierarchy,
  currently containing outline templates and an empty leaf.
- `AGENTS.md`: instructions for agents working in this project.

## Manual Creative-Writer Handoff

Open this repository as the creative-writer's working project and load the
[agent instructions](AGENTS.md). Supply the local
`.plans/CREATIVE_WRITER_HANDOFF.md` as the Season 1 writing request. The handoff
carries the lyrical story invitation; AGENTS.md carries workflow responsibilities,
knowledge boundaries, and deliverable expectations. The bible supplies canon.

The `.plans/` directory is ignored by Git. The local handoff is absent from public
clones and must be supplied separately when testing from another checkout.
Relative links in that Markdown file resolve from its own directory; repository
paths in agent instructions resolve from the project root.

## Writing and Performance Materials

Develop the [season outline](Script/Season_01/README.md) and
[episode outline](Script/Season_01/Episode_01/README.md) through the writing
workflow. Their current headings are templates, not established story events.
Treatments, skeletons, and performed scripts belong under `Script/`, outside the
bible. The `.gitkeep` preserves empty directories and can be removed when the
leaf contains real material.

During preparation, each scene receives its own `AGENTS.md`,
`dramatic_action_brief.md`, `performance_context.json`, `scene_skeleton.md`, and
initial `script.md` when the required inputs are available. Beat folders organize
material; canonical beat IDs and runtime handoff files provide traceability.
The runtime discovers scenes through those handoff files rather than directory
names. Season and episode divisions organize this theatrical work without
implying a television production.

## Adaptation and Template Provenance

This is an original adaptation of traditional Little Red Riding Hood motifs;
no particular edition supplies textual authority. The partner's directions and
adaptation choices are recorded in [project provenance](bible/project.md#authoritative-sources).

The initial template's section coverage drew on the user-provided
`prompt_biblia_cicatriz_perfecta.txt`. Only its organizational requirements were
used. That file is not needed to develop this project, and suggested synopsis
lengths in the templates are editorial guidance rather than runtime gates.

## Thematic Source

The partner supplied sections 1.1–1.4 of **GSA Order ADM 2325.8B,
Policy Statement on Harassment, Including Sexual and Non-sexual**, Office of
Civil Rights, as thematic material. This adaptation draws on the supplied
excerpt rather than a separately verified edition of the full directive.

The story carries the ideas through unwanted attention, judgments about who
someone is, kindness made conditional on personal closeness, favor tied to
receptiveness, the burden of fear upon an ordinary purpose, and the freedom to
refuse or speak without being made to suffer for it. Attribution belongs here;
the handoff and story express those concerns in the language of Red’s world.
The adaptation selects human tensions from the excerpt rather than reproducing
its definitions or attempting a one-to-one account of every provision.
