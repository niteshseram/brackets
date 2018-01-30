What's New in Release 1.12
-------------------------

*  **[JavaScript Refactoring](https://github.com/adobe/brackets/pull/13965)** by [navch](https://github.com/navch) :
You can now easily restructure JavaScript code using Refactor capabilities in Brackets. You can now rename, wrap in Try/Catch or Condition, Extract to Variable or Function, and Create Getters/Setters – all at the click of a button (or two!).
 

_Full change logs:_ [brackets](https://github.com/adobe/brackets/compare/release-1.11...release) and [brackets-shell](https://github.com/adobe/brackets-shell/compare/release-1.11...release#commits_bucket)



Community contributions to Brackets
-----------------------------------
* [Fix lgtm alerts](https://github.com/adobe/brackets/pull/13483) by [xiemaisi](https://github.com/xiemaisi)
* [Fix extension registry link in README.md](https://github.com/adobe/brackets/pull/13583) by [PikadudeNo1](https://github.com/PikadudeNo1)
* [Fix CTRL+Space handling while the CodeHintList is open](https://github.com/adobe/brackets/pull/13560) by [petetnt](https://github.com/petetnt)
* [Update strings.js [Croatian]](https://github.com/adobe/brackets/pull/13571) by [diomed](https://github.com/diomed)
* [On Windows force a 32 bit build until nodejs 64 bit is supported](https://github.com/adobe/brackets/pull/13384) by [ficristo](https://github.com/ficristo)
* [Fixes wrong function call in ProjectManager.js](https://github.com/adobe/brackets/pull/13611) by [hkirat](https://github.com/hkirat)
* [Fix typos [Croatian]](https://github.com/adobe/brackets/pull/13628) by [dbaric](https://github.com/dbaric)
* ["Getting Started" page in ukrainian language](https://github.com/adobe/brackets/pull/13397) by [yarik-vv](https://github.com/yarik-vv)
* [- add: doubleclick on search result header closes search results window](https://github.com/adobe/brackets/pull/13624) by [lukaszsobek](https://github.com/lukaszsobek)
* [Add mapping for stylus mode in LanguageManager](https://github.com/adobe/brackets/pull/13380) by [opl-](https://github.com/opl-)
* [Now reverse inspect can be disabled by setting the 'livedev.enableReverseInspect' pref to false](https://github.com/adobe/brackets/pull/13659) by [saurabh95](https://github.com/saurabh95)
* [Upgrade brackets-eslint to 3.2.0](https://github.com/adobe/brackets/pull/13717) by [ficristo](https://github.com/ficristo)


#### Pulling source code from Git
_TODO: any brackets-shell updates? which of the below messages are applicable?_

* A new brackets-shell build is _required_ for this sprint. Be sure to rerun `grunt setup` before building.
* Recommended: rebuild or reinstall an updated brackets-shell (no critical updates, but there are bugfixes).
* Rebuilding/updating brackets-shell is _optional_ for this release.
* Rebuilding/updating brackets-shell is _not_ required for this release.
* brackets-shell's Node dependencies have changed. Run `npm install` before rebuilding brackets-shell.
* Some submodules were updated this sprint. Run `git submodule update` to ensure your source tree is fully up to date.
* A submodule _URL_ was changed this sprint. Run `git submodule sync` and _then_ `git submodule update --init --recursive` to ensure your local source tree reflects the update.


Bugs fixed in Release 1.11
-------------------------
For details on the bugs addressed, please refer to [closed Release 1.11 bugs](https://github.com/adobe/brackets/issues?q=is%3Aclosed+milestone%3A%22Release+1.11%22). Not all fixed bugs will be caught by this search query, however.