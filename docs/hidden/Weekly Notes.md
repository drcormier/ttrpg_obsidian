---
tags:
  - notes
  - dungeons-and-dragons
  - saturday
---

# Notes For <% tp.date.now("dddd, YYYY-MM-DD") %>
<%*
	let title = tp.file.title
	if (title.startsWith("Untitled")) {
		title = `${tp.date.now("YYYY-MM-DD")} (${tp.date.now("dddd")})`;
	    await tp.file.rename(`${title}`);
	}
	tR += "Session began at " + tp.date.now("HH:mm:ss")
%>
## Current Characters
[[./Alyxia|Alyxia]]
[[./Blackavar|Blackavar]]
[[./Felix|Felix]]
[[./Sokar|Sokar]]
## Recurring Notes
>[!TIP] USE FAVORED BY THE GODS

>[!TIP] USE PROTECTION FROM EVIL AND GOOD AGAINST FIENDS AND TWIN SPELL IT

### Ring of Spell Storing
![[./Ring of Spell Storing|Ring of Spell Storing]]
### Teleporter Levels
![[./Teleporter|Teleporter]]
### Tiles
![[./Tiles|Tiles]]

## Notes
<% tp.file.cursor() %>
## Navigation
[[<% tp.date.now("YYYY-MM-DD (dddd)", -7) %>|←]] | [[<% tp.date.now("YYYY-MM-DD (dddd)", +7) %>|→]] 