# Notes For <% tp.date.now("dddd, YYYY-MM-DD") %>
<%*
	let title = tp.file.title
	if (title.startsWith("Untitled")) {
		title = `${tp.date.now("YYYY-MM-DD")} (${tp.date.now("dddd")}) (PM)`;
	    await tp.file.rename(`${title}`);
	} 
	tR += "Session began at " + tp.date.now("HH:mm:ss")
%>
## Current Characters
[[./Aura|Aura]]
[[./Cillian (Church) Grim|Church]]
[[./Kaelthorn|Kaelthorn]]
## Recap

## Notes
<% tp.file.cursor() %>