# v2.9.1 [#](https://github.com/idleberg/vscode-nsis/releases/tag/2.9.1)

* update `CHANGELOG.md`

# v2.9.0 [#](https://github.com/idleberg/vscode-nsis/releases/tag/2.9.0)

* refactored code
* update `devDependencies`

# v2.8.1 [#](https://github.com/idleberg/vscode-nsis/releases/tag/2.8.1)

- include `CHANGELOG.md`

# v2.8.0 [#](https://github.com/idleberg/vscode-nsis/releases/tag/2.8.0)

- allow case-insensitive syntax

# v2.7.3 [#](https://github.com/idleberg/vscode-nsis/releases/tag/2.7.3)

- organize syntax configuration into folder
- add `.vscodeignore`
- improve licensing description

# v2.7.2 [#](https://github.com/idleberg/vscode-nsis/releases/tag/2.7.2)

- stricter checks (hopefully fixing #5)

# v2.7.1 [#](https://github.com/idleberg/vscode-nsis/releases/tag/2.7.1)

- integrate `yarn.lock` into Travis CI tests

# v2.7.0 [#](https://github.com/idleberg/vscode-nsis/releases/tag/2.7.0)

- BridleNSIS: add `nsisHome` option
- BridleNSIS: additional error check
- fix typo in build notifications

# v2.6.2 [#](https://github.com/idleberg/vscode-nsis/releases/tag/2.6.2)

- BridleNSIS: improve error detection
- BridleNSIS: fix syntax pattern
- add `.jshintrc`

# v2.6.1 [#](https://github.com/idleberg/vscode-nsis/releases/tag/2.6.1)

- BridleNSIS: add and update syntax patterns

# v2.6.0 [#](https://github.com/idleberg/vscode-nsis/releases/tag/2.6.0)

- add syntax highlighting for BridleNSIS
- add IntelliSense for BridleNSIS
- add build command for BridleNSIS

# v2.5.11 [#](https://github.com/idleberg/vscode-nsis/releases/tag/2.5.11)

- extend highlighting support to transpiled [BridleNSIS](https://github.com/henrikor2/bridlensis) scripts

# v2.5.10 [#](https://github.com/idleberg/vscode-nsis/releases/tag/2.5.10)

- use local settings in build tasks

# v2.5.9 [#](https://github.com/idleberg/vscode-nsis/releases/tag/2.5.9)

- fix: wait for document to be saved before compiling

# v2.5.8 [#](https://github.com/idleberg/vscode-nsis/releases/tag/2.5.8)

- `nsl.tmLanguage`: update patterns in quotes

# v2.5.7 [#](https://github.com/idleberg/vscode-nsis/releases/tag/2.5.7)

- improve escape character pattern

# v2.5.6 [#](https://github.com/idleberg/vscode-nsis/releases/tag/2.5.6)

- modify build notifications
- fix unescaped `$` in scaffolding snippet

# v2.5.5 [#](https://github.com/idleberg/vscode-nsis/releases/tag/2.5.5)

- `core.Haskell.json`: fix unescaped `$` in scaffolding snippet

# v2.5.4 [#](https://github.com/idleberg/vscode-nsis/releases/tag/2.5.4)

- `core.Haskell.json`: fix Section snippets

# v2.5.3 [#](https://github.com/idleberg/vscode-nsis/releases/tag/2.5.3)

- fix badly escaped curly braces

# v2.5.2 [#](https://github.com/idleberg/vscode-nsis/releases/tag/2.5.2)

- add error notification for illegible build task creation
- create `.vscode` folder if necessary
- remove `getDefaultPrefix()`

# v2.5.1 [#](https://github.com/idleberg/vscode-nsis/releases/tag/2.5.1)

- add option whether to open generated build task
- update Haskell snippets

# v2.5.0 [#](https://github.com/idleberg/vscode-nsis/releases/tag/2.5.0)

- add command to create build task
- modify config handling

# v2.4.1 [#](https://github.com/idleberg/vscode-nsis/releases/tag/2.4.1)

- fix typo

# v2.4.0 [#](https://github.com/idleberg/vscode-nsis/releases/tag/2.4.0)

- add [Haskell](https://hackage.haskell.org/package/nsis) snippets
- makensis: log error to console
- nsL Assembler
  - log error to console
  - add build shortcut
- Linter bumped to Gulp v4
- update `README.md`
- update `devDependencies`

# v2.3.1 [#](https://github.com/idleberg/vscode-nsis/releases/tag/2.3.1)

- remove unused dependency

# v2.3.0 [#](https://github.com/idleberg/vscode-nsis/releases/tag/2.3.0)

- add [Output Channel](https://code.visualstudio.com/Docs/extensionAPI/vscode-api#OutputChannel) support for build commands (closes #4)
- add new options `showNotifications` and `alwaysShowOutput`
- remove task-runner snippets (replacements soon?)
- use `spawn` over `exec`

# v2.2.8 [#](https://github.com/idleberg/vscode-nsis/releases/tag/2.2.8)

- use `\t` in snippets

# v2.2.7 [#](https://github.com/idleberg/vscode-nsis/releases/tag/2.2.7)

- nsL Assembler: split up `entity.name.section.nsl` pattern

# v2.2.6 [#](https://github.com/idleberg/vscode-nsis/releases/tag/2.2.6)

- nsL Assembler: fix `entity.name.section.nsl` pattern

# v2.2.5 [#](https://github.com/idleberg/vscode-nsis/releases/tag/2.2.5)

- nsL Assembler
  - update syntax patterns
  - fix comment delimiter inside `#nsis` snippet

# v2.2.4 [#](https://github.com/idleberg/vscode-nsis/releases/tag/2.2.4)

- revert default transpiler flags
- improve build notifications
- update screenshot

# v2.2.2 [#](https://github.com/idleberg/vscode-nsis/releases/tag/2.2.2)

- improve build notifications
- update screenshot

# v2.2.1 [#](https://github.com/idleberg/vscode-nsis/releases/tag/2.2.1)

- modify default transpiler flags

# v2.2.0 [#](https://github.com/idleberg/vscode-nsis/releases/tag/2.2.0)

- nsL Assembler: add support for custom arguments

# v2.1.0 [#](https://github.com/idleberg/vscode-nsis/releases/tag/2.1.0)

- `nsl.tmLanguage`: add support for NSIS syntax inside #nsis blocks

# v2.0.2 [#](https://github.com/idleberg/vscode-nsis/releases/tag/2.0.2)

- simplified nsL build command
- rename build command
- update `devDependencies`

# v2.0.1 [#](https://github.com/idleberg/vscode-nsis/releases/tag/2.0.1)

- fix build system for nsL Assember

# v2.0.0 [#](https://github.com/idleberg/vscode-nsis/releases/tag/2.0.0)

- add language syntax for nsL Assembler
- add build system for nsL Assembler
- add IntelliSense for nsL Assembler
- improve `nlf.configuration.json`
- improve `nsis.configuration.json`

# v1.3.4 [#](https://github.com/idleberg/vscode-nsis/releases/tag/1.3.4)

- improve handling of `compilerArguments`

# v1.3.3 [#](https://github.com/idleberg/vscode-nsis/releases/tag/1.3.3)

- add `%PackEXEHeader` and `%UninstallExeName` to Drunken NSIS snippets

# v1.3.2 [#](https://github.com/idleberg/vscode-nsis/releases/tag/1.3.2)

- add more deprecated commands

# v1.3.1 [#](https://github.com/idleberg/vscode-nsis/releases/tag/1.3.1)

- update scope for `Function`, `PageEx`, `Section` and `SectionGroup` blocks

# v1.3.0 [#](https://github.com/idleberg/vscode-nsis/releases/tag/1.3.0)

(this really should have been `v1.2.1`, sorry!)
- add `$PROGRAMFILES32` and `$PROGRAMFILES64`
- fix scope for language variables

# v1.2.0 [#](https://github.com/idleberg/vscode-nsis/releases/tag/1.2.0)

- `nsis.tmLanguage`: split up core library patterns for better maintainability 
- `nlf.tmLanguage`: update patterns and scopes (merge from Sublime Text package)

# v1.1.1 [#](https://github.com/idleberg/vscode-nsis/releases/tag/1.1.1)

- remove deprecated commands
- add `SetPluginUnload` alias to Drunken NSIS

# v1.1.0 [#](https://github.com/idleberg/vscode-nsis/releases/tag/1.1.0)

- update `nsis.tmLanguage`
  - add support for variables/constants in quotes
  - add language variables
  - add core libraries
  - add highlighting of deprecated commands
  - modify scopes
- update `.travis.yml`
- fix unescaped `$` in snippets

# v1.0.2 [#](https://github.com/idleberg/vscode-nsis/releases/tag/1.0.2)

- escape ampersand in NLF syntax file

# v1.0.1 [#](https://github.com/idleberg/vscode-nsis/releases/tag/1.0.1)

- fix scaffolding snippet name

# v1.0.0 [#](https://github.com/idleberg/vscode-nsis/releases/tag/1.0.0)

- `nsis.tmLanguage`: improve RegEx patterns
- replace JSON linter
- remove Node 4 test
- update description

# v0.8.2 [#](https://github.com/idleberg/vscode-nsis/releases/tag/0.8.2)

- update `gulpfile.js`

# v0.8.1 [#](https://github.com/idleberg/vscode-nsis/releases/tag/0.8.1)

- `use babel` everywhere
- add `.eslintrc`

# v0.8.0 [#](https://github.com/idleberg/vscode-nsis/releases/tag/0.8.0)

- add strict build option

# v0.7.6 [#](https://github.com/idleberg/vscode-nsis/releases/tag/0.7.6)

- add description URL for Modern UI v1.x snippets

# v0.7.5 [#](https://github.com/idleberg/vscode-nsis/releases/tag/0.7.5)

- add missing description for `CreateShortcut`

# v0.7.4 [#](https://github.com/idleberg/vscode-nsis/releases/tag/0.7.4)

- improve documentation
- update dependencies

# v0.7.3 [#](https://github.com/idleberg/vscode-nsis/releases/tag/0.7.3)

- add description to install packaged extension (`.vsix`)

# v0.7.2 [#](https://github.com/idleberg/vscode-nsis/releases/tag/0.7.2)

- fix Modern UI scaffolding snippet
- modify scaffolding prefixes

# v0.7.1 [#](https://github.com/idleberg/vscode-nsis/releases/tag/0.7.1)

- modify default build keybinding (as suggested by guidelines)

# v0.7.0 [#](https://github.com/idleberg/vscode-nsis/releases/tag/0.7.0)

- add scaffolding-snippet for `task.json`

# v0.6.1 [#](https://github.com/idleberg/vscode-nsis/releases/tag/0.6.1)

- some house-keeping

# v0.6.0 [#](https://github.com/idleberg/vscode-nsis/releases/tag/0.6.0)

- add settings for build system

# v0.6.2 [#](https://github.com/idleberg/vscode-nsis/releases/tag/0.6.2)

- rename settings
- improve success message

# v0.5.1 [#](https://github.com/idleberg/vscode-nsis/releases/tag/0.5.1)

- modify build shortcut

# v0.5.0 [#](https://github.com/idleberg/vscode-nsis/releases/tag/0.5.0)

- add rudimentary build system
- fix `lineComment`

# v0.4.2 [#](https://github.com/idleberg/vscode-nsis/releases/tag/0.4.2)

- rename misnamed snippets

# v0.4.1 [#](https://github.com/idleberg/vscode-nsis/releases/tag/0.4.1)

- register missing snippets

# v0.4.0 [#](https://github.com/idleberg/vscode-nsis/releases/tag/0.4.0)

- add support for `MultiUser.nsh`
- add support for `StrStr.nsh`
- add support for `MUI2.nsh` (and `MUI.nsh`)
- improve descriptions for some of the snippets

# v0.3.0 [#](https://github.com/idleberg/vscode-nsis/releases/tag/0.3.0)

- merge descriptions from `atom-language-nsis@v5.0.0`

# v0.2.1 [#](https://github.com/idleberg/vscode-nsis/releases/tag/0.2.1)

- update description

# v0.2.0 [#](https://github.com/idleberg/vscode-nsis/releases/tag/0.2.0)

- add support for NSIS Language Files (.nlf)

# v0.1.1 [#](https://github.com/idleberg/vscode-nsis/releases/tag/0.1.1)

- add screenshot
- fix scaffolding snippets

# v0.1.0 [#](https://github.com/idleberg/vscode-nsis/releases/tag/0.1.0)

- first release

