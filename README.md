Dash.tmbundle
=============

TextMate Bundle to integrate with [Dash][]

The `Open in Dash` command will search for the current selected text or word.
It is bound to ⌃⌥H for all source files.

You can filter the search results by setting `TM_DASH_PREFIX` to the appropriate prefix.
For example, in your `~.tm_properties` you could have:

	[source.python]
	TM_DASH_PREFIX = 'python:'

	[source.ruby]
	TM_DASH_PREFIX = 'ruby:'

[Dash]: http://itunes.apple.com/us/app/dash-docs-snippets/id458034879?mt=12