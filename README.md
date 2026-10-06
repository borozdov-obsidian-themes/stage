# Borozdov Stage

A theme from the Borozdov collection. Two faces — light **Spotlight**, a white stage with
lilac washes, and dark **Backstage**, the same stage with the house lights down. Airy
near-white canvas, oversized geometric headlines, soft 16px cards and one aubergine for
what you send.

![Borozdov Stage in light mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/stage/main/screenshots/light.png)

![Borozdov Stage in dark mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/stage/main/screenshots/dark.png)

## Principles

- **A white stage.** The page stays airy and monochrome; the side panels take a faint
  lilac wash so the note is the brightest thing on screen.
- **Pools of aubergine.** Colour appears as concentrated pools — a checked task, a toggle,
  the main button, the open file in the sidebar — never as a tint over everything.
- **Two voices.** Montserrat Bold for the title and headings, tracked in tight like a
  geometric display face; the platform's own sans for the text.
- **Lilac for labels.** Tags and property values are lilac pills with a lavender rim and
  a plum label; callouts are light washes of their type's colour with a soft rim.

## Features

- Light and dark modes, following Settings → Appearance → Base color scheme
- Callouts as washed cards with a whisper of lift; the title in the type's colour
- Tables as white cards with a lilac header band and eyebrow labels
- Channel-blue links, aubergine caret
- Quiet editing: no focus ring around the note, its title or form fields while you type;
  property names read as labels, not boxed fields
- Text colours meet WCAG contrast on both faces
- The phone layout keeps the same colours and shapes
- No `!important`: every rule can be overridden with a CSS snippet

## Installation

**From the community directory, as a variant:** this theme ships inside **Borozdov
Console**. Install Borozdov Console under Settings → Appearance → Themes → Manage, then
the [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin, and
choose **Stage** under Style Settings → Borozdov Console → Variant. The variant brings
this theme's palette, type and corners; its own layout, and its embedded font if it has
one, come with the full theme below.

**The full theme, by hand:** download `manifest.json` and `theme.css` from the
[latest release](https://github.com/borozdov-obsidian-themes/stage/releases/latest) into
`<vault>/.obsidian/themes/Borozdov Stage/`, then choose Borozdov Stage under
Settings → Appearance → Themes.

## Font

Montserrat Bold (© 2011 The Montserrat Project Authors) is embedded in `theme.css` as
base64 WOFF2 under the SIL Open Font License 1.1 — see [`fonts/OFL.txt`](fonts/OFL.txt).
One weight, Latin and Cyrillic, headlines only.

## License

MIT — see [LICENSE](LICENSE).

---

**По-русски.** Тема из коллекции Borozdov. Два лика: светлый «Прожектор» — белая сцена с
сиреневыми заливками, и тёмный «Закулисье» — та же сцена при погашенном свете. Воздушный
почти белый холст, крупные геометрические заголовки (Montserrat), мягкие карточки 16px и
один баклажановый для того, что вы отправляете. В каталоге тема живёт вариантом Borozdov Console: установите Borozdov Console и плагин Style Settings, затем выберите Stage в Style Settings → Borozdov Console → Variant. Целиком, со своей вёрсткой, тема ставится вручную из последнего релиза репозитория.
