What's New in Release 1.10
-------------------------

*  **[Multiple encoding support](https://github.com/adobe/brackets/pull/13412)** by [saurabh95](https://github.com/saurabh95) :
Brackets now supports more than 40 different file encodings. You can now Open/Save files with different encodings.
 
*  **[Forward/Backward navigation in edit history](https://github.com/adobe/brackets/pull/13418)** by [swmitra](https://github.com/swmitra) :
Navigate backward/forward using Alt-I, Alt-Shift-I across explicit cursor positions.
 
*  **[Enable/Disable default extensions](https://github.com/adobe/brackets/pull/13044)** by [saurabh95](https://github.com/saurabh95) :
You can now enable/disable default extensions, that are shipped with Brackets.
 
*  **[Search History](https://github.com/adobe/brackets/pull/13237)** by [saurabh95](https://github.com/saurabh95) :
Access all your most recently searched queries from the search bar. 
 
*  **[Native Menus for Linux](https://github.com/adobe/brackets-shell/pull/602)** by [eyelash](https://github.com/eyelash) and [saurabh95](https://github.com/saurabh95) :
HTML menus are replaced with native menus in Linux.
 
*  **[@rule and pseudo-selector code hints](https://github.com/adobe/brackets/pull/13295)** by [swmitra](https://github.com/swmitra) :
CSS code hints now support @rule and pseudo selector/element code hints. 
 
*  **[Inline CSS code hints](https://github.com/adobe/brackets/pull/13270)** by [swmitra](https://github.com/swmitra) :
Brackets now provides CSS code hints in style attribute value in html.


_Full change logs:_ [brackets](https://github.com/adobe/brackets/compare/release-1.9...release-1.10#commits_bucket) and [brackets-shell](https://github.com/adobe/brackets-shell/compare/release-1.9...release-1.10#commits_bucket)



Known Issues
------------
* _Debug > Run Tests_ is disabled in the installer/DMG distributions of Brackets, because the unit test code is not included. To run unit tests, [pull Brackets from GitHub](https://github.com/adobe/brackets/wiki/How-to-Hack-on-Brackets#wiki-getcode) instead.


Community contributions to Brackets
-----------------------------------


#### Pulling source code from Git
_TODO: any brackets-shell updates? which of the below messages are applicable?_

* A new brackets-shell build is _required_ for this sprint. Be sure to rerun `grunt setup` before building.
* Recommended: rebuild or reinstall an updated brackets-shell (no critical updates, but there are bugfixes).
* Rebuilding/updating brackets-shell is _optional_ for this release.
* Rebuilding/updating brackets-shell is _not_ required for this release.
* brackets-shell's Node dependencies have changed. Run `npm install` before rebuilding brackets-shell.
* Some submodules were updated this sprint. Run `git submodule update` to ensure your source tree is fully up to date.
* A submodule _URL_ was changed this sprint. Run `git submodule sync` and _then_ `git submodule update --init --recursive` to ensure your local source tree reflects the update.


Bugs fixed in Release 1.10
-------------------------
For details on the bugs addressed, please refer to [closed Release 1.10 bugs](https://github.com/adobe/brackets/issues?q=is%3Aclosed+milestone%3A%22Release+1.10%22). Not all fixed bugs will be caught by this search query, however.