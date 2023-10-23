---
tags:
  - notes
  - pathfinder
  - sunday
---

# Notes For <% tp.date.now("dddd, YYYY-MM-DD") %>
<%*
	let title = tp.file.title
	if (title.startsWith("Untitled")) {
		title = `${tp.date.now("YYYY-MM-DD")} (${tp.date.now("dddd")}) (AV)`;
	    await tp.file.rename(`${title}`);
	} 
	tR += "Session began at " + tp.date.now("HH:mm:ss")
%>
## Current Characters
[[./Dredd|Dredd]]
[[./Hannya|Hannya]]
[[./Lyra|Lyra]]
[[./Swan|Swan]]
[[./Warden|Warden]]
## Recurring Notes
![[./Lyra Items|Lyra Items]]
## Notes
<% tp.file.cursor() %>
## Navigation
[[<% tp.date.now("YYYY-MM-DD (dddd)", -7) %>|←]] | [[<% tp.date.now("YYYY-MM-DD (dddd)", +7) %>|→]] 