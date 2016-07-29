# Custom jQuery Selectors
jQuery provides some great basic selectors, but sometimes we need something outside of what's given. For example, if you are finding an option inside a select box with exact value, you end up using **:contains** selector which gives you the best match as it checks for substrings.

Example:

	<script type="text/javascript">
		$("#selectbox option:contains(car)").attr("selected", "selected");
	</script>
	
This will return multiple matches as **car** as well as **carpet**. For such scenarios, a few new (maybe not new) have been provided in a single file, which you can include in your projects.