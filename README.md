# Studio Five Corp: Branding Skills

Agent skills that apply the **Studio Five Corp Branding Guidelines 2027**. Use them to make or review on-brand websites, footers, proposals and decks, email signatures, social posts, YouTube thumbnails, video, print and copy.

**Bright. Precise. Full of energy.** Cobalt `#0046AE` · Energy blue `#4CC9F0` · Fresh lime `#D4F725` · Clash Display + Satoshi.

## Skills

| Skill | What it does |
|---|---|
| [`studio-five-corp-brand`](skills/studio-five-corp-brand/SKILL.md) | Core brand rules (five colours and their reading pairs, Clash Display/Satoshi, the uppercase logo family, no-slogan rule, voice, spacing), defaults for each format, a redesign workflow and the review checklist (READY / REVISE / CLARIFY). |

```
skills/studio-five-corp-brand/
├── SKILL.md                      # rules used on almost every task
├── references/brand-book-2027.md # full 102-page brand book as Markdown, sections 00–09
└── assets/tokens.css             # colour, type, spacing and layout tokens
```

## Install

**Claude Code:** copy the skill folder into your skills directory:

```bash
git clone https://github.com/doniwirawan/studio-five-corp-brand-skill
cp -r studio-five-corp-brand-skill/skills/studio-five-corp-brand ~/.claude/skills/
```

**Claude.ai:** zip `skills/studio-five-corp-brand/` and upload it under *Settings → Capabilities → Skills*.

**Other agents:** `SKILL.md` is plain Markdown with YAML front matter. Point any agent that supports skills, or a system prompt, at the folder.

The skill loads automatically for any task that mentions Studio Five Corp, studiofivecorp.com or the Corp palette. You can also ask for it directly ("make this on-brand", "brand review this proposal").

## Related

- [studio-five-spaces-branding-skills](https://github.com/doniwirawan/studio-five-spaces-branding-skills): the same kind of skill for Studio Five Spaces.

## Not included

The logo SVG/PDF/EPS masters and the font files aren't in this repo. The skill links to the hosted PNG logos. Get the masters from the Corp brand owner and the fonts from [Fontshare](https://www.fontshare.com/). Never redraw the logo in a font.

## License

The skill text, Markdown and CSS are released under the [MIT License](LICENSE). The Studio Five Corp name, logos and brand identity are trademarks of Studio Five Corp Pte Ltd and are **not** covered by that license. Use them only to make work for Studio Five Corp.
