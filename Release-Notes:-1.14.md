What's New in Release 1.14
-------------------------
* [AutoUpdate Framework](https://github.com/adobe/brackets/pull/14177) by [mbhavi](https://github.com/mbhavi) : You can now automatically update Brackets, without leaving the code editor.
* [Add drag and drop to move items in FileTreeView](https://github.com/adobe/brackets/pull/13546) by [boopeshmahendran](https://github.com/boopeshmahendran) : You can now manipulate folder structure from within Brackets. Move a file/folder from one folder to another with a simple drag and drop.
* [Enable opening of remote(http|https) files in Brackets](https://github.com/adobe/brackets/pull/14153) by [swmitra](https://github.com/swmitra) : You can now open a remotely hosted web-page from within Brackets. Use Ctrl/Cmd-Shift-O shortcut and supply a URL to quickly open the file and review the code within Brackets.


_Full change logs:_ [brackets](https://github.com/adobe/brackets/compare/release-1.13...release#commits_bucket) and [brackets-shell](https://github.com/adobe/brackets-shell/compare/release-1.13...release#commits_bucket)

Community contributions to Brackets
-----------------------------------


* [Forcefully disabling renderer accesibility](https://github.com/adobe/brackets-shell/pull/660) by nethip
* [Executing default update process handler, in case auto-update fails.](https://github.com/adobe/brackets/pull/14605) by nethip
* [AutoUpdate Mac Installer Script Administrator privileges changes](https://github.com/adobe/brackets-shell/pull/656) by [niteskum](https://github.com/niteskum)
* [Linux window size and position ](https://github.com/adobe/brackets-shell/pull/636) by [pelatx](https://github.com/pelatx)
* [Upgrading node to v6.14.0](https://github.com/adobe/brackets-shell/pull/653) by [subhashjha333](https://github.com/subhashjha333)
* [Auto Update Error Handlng Fix](https://github.com/adobe/brackets/pull/14412) by [niteskum](https://github.com/niteskum)
* [JSRefactoring Bugs Fix](https://github.com/adobe/brackets/pull/14455) by [niteskum](https://github.com/niteskum)
* [Fixed ExtractToVariable Menu Close Issue due to scrolling](https://github.com/adobe/brackets/pull/14492) by [niteskum](https://github.com/niteskum)
* [Fixed Getter Setter Redo Issue](https://github.com/adobe/brackets/pull/14508) by [niteskum](https://github.com/niteskum)
* [jsRefactor Rename Relative Path issue fixed](https://github.com/adobe/brackets/pull/14520) by [niteskum](https://github.com/niteskum)
* [Add styles for stickyhighlight feature in livepreview](https://github.com/adobe/brackets/pull/14546) by [boopeshmahendran](https://github.com/boopeshmahendran)
* [Enable DOMAgent in live preview](https://github.com/adobe/brackets/pull/14561) by [debajyotide](https://github.com/debajyotide)
* [Add a method to get live doc parent path](https://github.com/adobe/brackets/pull/14564) by [debajyotide](https://github.com/debajyotide)
* [Fixing the mac debug build](https://github.com/adobe/brackets-shell/pull/657) by [vickramdhawal](https://github.com/vickramdhawal)
* [Update CSSProperties.json for text-align and text-justify](https://github.com/adobe/brackets/pull/14563) by [narayani28](https://github.com/narayani28)
* [Update notification - based on current platform](https://github.com/adobe/brackets/pull/14655) by [swmitra](https://github.com/swmitra)
* [Language Server Protocol Support for Brackets](https://github.com/adobe/brackets/pull/14606) by [subhashjha333](https://github.com/subhashjha333)
* [Language Server Protocol Support for Brackets - Fix Author](https://github.com/adobe/brackets/pull/14678) by [shubhsnov](https://github.com/shubhsnov)
* [Revert "Language Server Protocol Support for Brackets - Fix Author"](https://github.com/adobe/brackets/pull/14680) by [shubhsnov](https://github.com/shubhsnov)
* [Php Tooling Extensions Using LSP Framework](https://github.com/adobe/brackets/pull/14671) by [niteskum](https://github.com/niteskum)
* [switching from anonymous to pseudonymous to align with the definition…](https://github.com/adobe/brackets/pull/14687) by [niteskum](https://github.com/niteskum)
* [Removing the old Brackets CLA check](https://github.com/adobe/brackets/pull/14684) by [shubhsnov](https://github.com/shubhsnov)
* [Fixed LSP Linting Synchronization Issues](https://github.com/adobe/brackets/pull/14685) by [niteskum](https://github.com/niteskum)
* [Php Tooling Strings changes](https://github.com/adobe/brackets/pull/14688) by [niteskum](https://github.com/niteskum)
* [Fix for "GetItNow" action behaviour](https://github.com/adobe/brackets/pull/14691) by [swmitra](https://github.com/swmitra)
* [Sending Analytics Data for file Operation and LSP features](https://github.com/adobe/brackets/pull/14683) by [niteskum](https://github.com/niteskum)
* [Fix for PHPCodeHints invocation failure scenarios](https://github.com/adobe/brackets/pull/14692) by [shubhsnov](https://github.com/shubhsnov)
* [PHPCodeHints : Select initial element in the hint list](https://github.com/adobe/brackets/pull/14694) by [shubhsnov](https://github.com/shubhsnov)
* [Fix : Error occurs when dismissing QuickOpen dialog when no document is open](https://github.com/adobe/brackets/pull/14698) by [shubhsnov](https://github.com/shubhsnov)
* [Changes to send data only once per 24 hours](https://github.com/adobe/brackets/pull/14695) by [SnchitGrover](https://github.com/SnchitGrover)
* [Adding Code Hints Description Box for handling additional hint information in LSP](https://github.com/adobe/brackets/pull/14696) by [shubhsnov](https://github.com/shubhsnov)
* [Capability to Support Document & Project Symbols provided by a Language Server](https://github.com/adobe/brackets/pull/14697) by [shubhsnov](https://github.com/shubhsnov)
* [LSP Find References Feature](https://github.com/adobe/brackets/pull/14693) by [niteskum](https://github.com/niteskum)


#### Pulling source code from Git
_TODO: any brackets-shell updates? which of the below messages are applicable?_

* A new brackets-shell build is _required_ for this sprint. Be sure to rerun `grunt setup` before building.
* Recommended: rebuild or reinstall an updated brackets-shell (no critical updates, but there are bugfixes).
* Rebuilding/updating brackets-shell is _optional_ for this release.
* Rebuilding/updating brackets-shell is _not_ required for this release.
* brackets-shell's Node dependencies have changed. Run `npm install` before rebuilding brackets-shell.
* Some submodules were updated this sprint. Run `git submodule update` to ensure your source tree is fully up to date.
* A submodule _URL_ was changed this sprint. Run `git submodule sync` and _then_ `git submodule update --init --recursive` to ensure your local source tree reflects the update.


Bugs fixed in Release 1.14
-------------------------
For details on the bugs addressed, please refer to [closed Release 1.14 bugs](https://github.com/adobe/brackets/issues?q=is%3Aclosed+milestone%3A%22Release+1.14%22). Not all fixed bugs will be caught by this search query, however.