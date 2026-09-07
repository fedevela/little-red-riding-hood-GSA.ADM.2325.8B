# Little Red Riding Hood

A two-character theatrical adaptation for forum theatre. Red's journey meets the
Wolf's patient pursuit; the story gathers toward a danger whose outcome remains
unresolved. The [story bible](bible/README.md) establishes the characters, world,
and dramatic foundations. Season 1 is the current writing assignment.

## Project Layout

- `bible/`: project, cast, world rules, themes, dramatic arcs, and relationships.
- `bible/characters/little_red_riding_hood/` and `bible/characters/wolf/`: the two
  complete profiles, each organized by the director’s [seven character
  dimensions](bible/README.md#the-directors-seven-character-dimensions).
- `Script/season_template/Season_N/Episode_N/script.md`: a blank episode manuscript
  containing all its scenes and beats; [Script guide](Script/README.md) holds the generic template.
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

## Runtime Compatibility

This bible now uses the director’s seven character dimensions. The current
creative-writer runtime still names and validates the former profile filenames
in `prompts.py` and `artifact_validation.py`. Its character-file contract must be
adapted before an automated run can accept this structure. The runtime update
is pending; the profiles are ready for manual reading and development.

## Markdown Script Template

The [Script guide](Script/README.md) holds the generic Markdown template and
formatting conventions. [Episode N](Script/season_template/Season_N/Episode_N/script.md)
is a blank manuscript with front matter, act and scene headings, character cues,
dialogue, directions, and an internal beat marker. Each episode document contains
all its scenes and beats. The manuscript scaffold remains neutral until story writing begins.

## Writing and Performance Materials

Develop the [season outline](Script/season_template/Season_N/README.md) and
[episode outline](Script/season_template/Season_N/Episode_N/README.md) through the writing
workflow. Their current headings are templates, not established story events.
Treatments, skeletons, and performed scripts belong under `Script/`, outside the
bible. Each episode has one manuscript file containing its scenes and beats.

Scene preparation and roundtable context remain distinct from the episode’s
manuscript. The current creative-writer runtime expects scene-level materials,
including `script.md`, and discovers scenes through its handoff files. Adapting
that delivery contract to the episode manuscript is pending alongside the
character-profile update. The template establishes the intended manuscript
structure; runtime code remains unchanged.

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
