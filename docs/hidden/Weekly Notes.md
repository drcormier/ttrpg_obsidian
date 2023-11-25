---
tags:
  - notes
  - friday
  - pathfinder
date created: Thursday, September 28th 2023, 5:30:32 pm
date modified: Friday, October 27th 2023, 9:39:26 am
share: "true"
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
[[./Cozmo|Cozmo]]
[[./Fentress Seraphina|Fen]]
[[./Grent|Grent]]
[[./Lysswyn|Lysswyn]]
[[./Vathal Moonseeker|Vathal]]
## Recurring Notes
[LegendKeeper Wiki](https://app.legendkeeper.com/a/worlds/cl9i3wvwfuxpk0990vdj471tg/cl9i3xygz000d0288hoamypix)
[[./Lysswyn's Personality|Lysswyn's Personality]]
## Notes
<% tp.file.cursor() %>
## Navigation
[[<% tp.date.now("YYYY-MM-DD (dddd)", -7) %>|←]] | [[<% tp.date.now("YYYY-MM-DD (dddd)", +7) %>|→]]