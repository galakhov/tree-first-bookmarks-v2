# Tree First Bookmarks

### This fork of <a href="https://github.com/ardcore/chrome-better-bookmark">"Better Bookmark"</a> is heavily optimised for people got used to the hierarchical folders' structure in their bookmarks and wants to stick to it having tons of (organised) folders.

This extension _is meant for a quick classification & saving a bookmark_ into some particular folder only. It helps to filter out & find this one folder among a huge set of folders and sub-folders or to create a new folder with a desired name. It is _not meant to look for your saved bookmarks nor open any bookmark_, as this action is possible in chrome by default.

By clicking on any radio button in the folder's list or in an opened sub-tree, you'll see the breadcrumb navigation with the full path to a chosen folder. After clicking on any radio button, the origin (a parent folder) is set. The sub-tree view will always display the sub-folders in this parent folder if there are any. Then, if you enter a name for a new folder in the above entry field and save it by clicking on this name, it will be placed as a sub-folder into this chosen origin. If no origin has been chosen, the default location new folders are saved to is the "Other Bookmarks" folder.

For easy orientation tooltips are attached to every listed category.

- Better Bookmark has been renamed to "Tree First Bookmarks" and gets a new icon from now on.
- The redesign has happened. I tried to simplify the UI and keep the original miminalistic style as far as possible, however, I'm not a web-designer and am open to a reasonable suggestions.
- Better-Bookmark-Button extension is now equipped with captions showing up the full path to the current bookmark on a hovered category.
- Now you can also choose the parent directory for the new folder that is being created (in the old original version all folders were first put into the "Other Bookmarks" folder allowing only a flat structure, i.e. no hierarchy).
- Another new feature — _The Sub Tree_ — helps you to get a quick overview of sub-folders in a chosen directory (click on any radio button to activate it).
- UI has been also improved. Arrows, breadcrumb and descriptions were added, input fields and text blocks were moved to key positions.
- Fuse.js library (fuzzy search) updated to v3.3.0 and max amount of characters for the search pattern has been changed, therefore, "Pattern length is too long" error shouldn't now block the search (or bitapRegexSearch will be used instead).
- Clickable breadcrumbs allow you to change a parent directory (to go up/down the tree) by clicking on one of the links in a breadcrumb (start by clicking any radio button).

<p align="center"><img width="320" src="https://raw.githubusercontent.com/galakhov/tree-first-bookmarks/master/screenshot.png" title="Tree First Bookmarks" alt="Tree First Bookmarks"></p>

# Original chrome-better-bookmark

Chrome Extension that lets you easily add bookmarks to any category. It includes spotlight-like weighted search (http://fusejs.io) with mouse/keyboard support. Following features were implemented in order to simplify the navigation: the breadcrumb, the sub-tree with the its switchable state and the captions with the full path for every node.

The new advanced _Tree First Bookmarks_ extension can be found here: https://chrome.google.com/webstore/detail/tree-first-bookmarks/lempbilidejiiljkciadplnekoflbmnl

_The old original version of this extension can still be found here_: https://chrome.google.com/webstore/detail/better-bookmark/pniopfmciclllcpockpkgceikipiibol

# key binding: cmd + b / ctrl + b

Chrome allows you to set your own key binding for every extension. See https://github.com/ardcore/chrome-better-bookmark/issues/1

# TODO's

- [ ] Show the location of the bookmark as the full path in the breadcrumb when a user opens the extension and the page was already bookmarked
- [ ] Add options (font size and style, focus style, key bindings, sorting options, etc.)
- [ ] Add the position variants (top or bottom) of the tooltip into the extension's options
- [ ] TBD: icon should be greyed out by default, highlighted if the page is already bookmarked
- [x] TBD: subcategory indentation
- [x] Default state of the children's toggler (if a user navigates between nodes it switches back to the disabled state)

# Thanks to

Big thanks goes to [ardcore](https://github.com/ardcore) and his initial version of open sourced repo of [chrome-better-bookmark](https://github.com/ardcore/chrome-better-bookmark)s.

The evolution of development and the related pull request can be found [here](https://github.com/ardcore/chrome-better-bookmark/pull/6).
