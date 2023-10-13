---
tags:
  - notes
  - dungeons-and-dragons
  - tuesday
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
[[./Agath|Agath]]
[[./Cade|Cade]]
[[./Ko|Ko]]
[[./Liera|Liera]]
[[./Lucio|Lucio]]
[[./Wuender|Wuender]]
## Recurring Notes
![[./Recurring Notes|../Templates/Recurring Notes]]
## Notes
<% tp.file.cursor() %>
## Navigation
[[<% tp.date.now("YYYY-MM-DD (dddd)", -7) %>|←]] | [[<% tp.date.now("YYYY-MM-DD (dddd)", +7) %>|→]] 