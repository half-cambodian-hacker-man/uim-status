# uim-status

A small utility to get the current status of `uim`.

## Why?

uim doesn't have a command-line tool to see which IM is currently active, with this tool, you can run `uim-status | grep selected | cut -d $'\t' -f 1` to get the name of the currently selected IM.
