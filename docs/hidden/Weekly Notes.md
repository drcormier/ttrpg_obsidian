---
tags:
  - notes
  - dungeons-and-dragons
  - wednesday
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
[[./Greyan|Greyan]]
[[./Leviticus|Leviticus]]
[[./Othello|Othello]]
[[./Velphi|Velphi]]
[[./Vera|Vera]]
## Recurring Notes
### Spell Scrolls
![[./Spell Scrolls|Spell Scrolls]]
[[./Velphi's Personality|Velphi's Personality]]
## Notes
<% tp.file.cursor() %>
## Navigation
[[<% tp.date.now("YYYY-MM-DD (dddd)", -7) %>|←]] | [[<% tp.date.now("YYYY-MM-DD (dddd)", +7) %>|→]] 