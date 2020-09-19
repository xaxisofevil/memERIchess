# memERIchess
TODO:
	selection tree should be a full-height sidebar style menu selector on the right side of the page
	selection tree should communicate with the board AI, telling it what is currently selected
	board AI will select a line from the openings.db sqlite3 db by:
		select line from opening_table where (opening in list given by selection tree) and (current time is greater than your line due date) order by weight desc limit 1
	board AI needs to be a single-file-component, so it can handle triggering style animations and include the control buttons
