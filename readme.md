## Brave Bookmarks

### Brave version of [Chrome Bookmarks](https://travis-ci.org/blainesch/alfred-chrome-bookmarks)
*For Alfred 3*

Searches through your current Brave bookmarks. This does not cache them in a database, but reads directly from the JSON bookmarks file. This makes it drastically faster.

This will search through the name of your bookmark and the URL. It will split your query into grams for inclusive matching and a ranking system to show relevant results first.

## Multiple or Single Profiles

By default it will search *all of your profiles*, if you wish to just search one profile you can modify the profile path. If you open the workflow in Alfred you can double click the "Script Filter" to edit it. You can see a `PROFILE` item that points to the path of your profile. By default it looks like:

~~~
PROFILE="~/Library/Application Support/BraveSoftware/Brave-Browser/**/Bookmarks" php
bookmarks.php {query}
~~~

Simply change `~/Library/Application Support/BraveSoftware/Brave-Browser/**/Bookmarks` to the
single path.

For example:
* `~/Library/Application Support/BraveSoftware/Brave-Browser/Default/Bookmarks`
* `~/Library/Application Support/BraveSoftware/Brave-Browser/Profile 2/Bookmarks`

## Provided as is

This is my first fork of something, so if I've missed proper attributions, licensing, etc. really sorry about that.
