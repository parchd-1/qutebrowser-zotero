# qutebrowser-zotero
A userscript (in the future, maybe a plugin) to connecto qutebrowser to zotero standalone

## Installation

Copy to your qutebrowser userscript directory (see https://www.qutebrowser.org/doc/userscripts.html)
aliases (recommended):

`:set aliases zotero "spawn --userscript zotero"`
`:set aliases Zotero "hint links userscript zotero"`

## Usage

If using the aliases above, use `:zotero` to save an item from the current page, or the page itself as a snapshot if no translator exists. Use `:Zotero` to save the target of a link using hints.

## Limitations

Because the userscript can't access qutebrowser's cookies, sites which require authentication might not work.
Currently sciencedirect isn't working, possibly as a result of not being able to log in.
