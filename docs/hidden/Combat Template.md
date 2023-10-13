<%*
	let title = tp.file.title
	if (title.startsWith("Untitled")) {
		title = tp.date.now("YYYY-MM-DD") + " Combat No. " + await tp.system.prompt("Combat Number");
	    await tp.file.rename(`${title}`);
	} 
	tR += "Combat began at " + tp.date.now("HH:mm:ss")
%>
# Combatants
## PCs
[[./Kuramira|Kuramira]]
[[./Fuq|Fuq]]
[[./Alvaungh|Alvaungh]]
## NPCs

## Enemies

# Other Notes
