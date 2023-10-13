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
[[./Revvie|Revvie]]
[[./Curi|Curi]]
[[./Celadon|Celadon]]
## Notes
<% tp.file.cursor() %>