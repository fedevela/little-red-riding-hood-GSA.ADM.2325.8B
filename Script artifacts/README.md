# Script

## Manuscript Structure

The blank manuscript lives in `../Script/season_template/Season_N/Episode_N/`;
outline templates live here in `season_template/Season_N/Episode_N/`.
Replace `N` with the appropriate numbers when creating a season from the template.

Seasons contain episodes. Each episode has one `script.md` containing its front
matter, acts, scenes, and all their beats. Scene headings divide the manuscript;
beat markers identify changes in dramatic purpose within each scene. Add speeches
and directions beneath each marker as the episode develops.

- [Season outline](season_template/Season_N/README.md)
- [Episode outline](season_template/Season_N/Episode_N/README.md)
- [Episode N — blank manuscript](../Script/season_template/Season_N/Episode_N/script.md)

## Markdown Play Format

The template below follows the supplied American play-script conventions.
Replace bracketed fields with the manuscript’s details and repeat character
entries, scenes, speeches, and beat blocks as needed. Front matter opens the
episode manuscript once, followed by its acts and scenes.

| Element | Markdown representation | Page layout when exported |
| --- | --- | --- |
| Title page | Title heading and playwright name. | Center title and playwright. |
| Dramatis personae | Uppercase character names with age, gender, and relevant traits. | Begin on its own introductory page. |
| Setting and time | Separate place and time fields. | Present before the dramatic text. |
| Act and scene headings | Uppercase headings. | Center; underline if desired. |
| Character cues | Bold uppercase names followed by a hard line break. | Center or indent about four inches from the left margin. |
| Dialogue | Sentence case directly below the cue, without quotation marks. | Left-align at the standard text margin. |
| Stage directions | Blockquotes containing italicized parentheses. | Indent from both left and right margins. |
| Inline directions | Italicized parentheses inside the dialogue paragraph. | Keep within the dialogue block. |

Markdown supplies the textual structure. The renderer or export stylesheet
controls exact centering, margins, underlining, and page breaks. Horizontal rules separate front-matter sections in this source.
Two trailing spaces after a character cue place speech on the next line.

Beat markers use Markdown HTML comments, such as
`<!-- Beat [ID]: [Dramatic purpose or change]. -->`. They remain visible in the
source for writing and traceability and stay hidden in the rendered manuscript.
Keep all scene headings, beat markers, and dialogue in the episode’s `script.md`.

## Blank Manuscript Template

```markdown
# [PLAY TITLE]

[Playwright name]

---

# DRAMATIS PERSONAE

**[CHARACTER NAME]** — [Age description], [gender, as established], [relevant traits].

---

# SETTING & TIME

**Place:** [Where the play takes place.]

**Time:** [When the play takes place.]

---

## ACT [NUMBER]

### SCENE [NUMBER] — [SCENE TITLE]

> *([Setting at the opening of the scene.])*

<!-- Beat [ID]: [Dramatic purpose or change]. -->

> *([Stage direction: action or movement.])*

**[CHARACTER NAME]**  
[Dialogue in normal sentence case.]

**[CHARACTER NAME]**  
[Dialogue before an inline direction.] *([Brief action or emotional cue.])* [Dialogue continues.]

> *([Stage direction between speeches.])*

<!-- Repeat the beat marker and speech/direction blocks within this scene as needed. -->

<!-- Repeat the scene heading and its beat blocks for each subsequent scene in this episode. -->
```
