<%*
	let title = tp.file.title
	if (title.startsWith("Untitled")) {
		title = await tp.system.prompt("Settlement name", throw_on_cancel=true);
	    await tp.file.rename(`${title}`);
	} 
%>
## Settlement <% tp.system.prompt("Settlement level", throw_on_cancel=true) %>
### Government

### Population

### Languages

### Religions

### Other

### People

### Locations