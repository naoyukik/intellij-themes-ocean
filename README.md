# intellij-themes-ocean

![Build](https://github.com/naoyukik/intellij-themes-ocean/workflows/Build/badge.svg)
[![Version](https://img.shields.io/jetbrains/plugin/v/PLUGIN_ID.svg)](https://plugins.jetbrains.com/plugin/PLUGIN_ID)
[![Downloads](https://img.shields.io/jetbrains/plugin/d/PLUGIN_ID.svg)](https://plugins.jetbrains.com/plugin/PLUGIN_ID)

## Template ToDo list
- [x] Create a new [IntelliJ Platform Plugin Template][template] project.
- [ ] Get familiar with the [template documentation][template].
- [ ] Adjust the [pluginGroup](./gradle.properties), [plugin ID](./src/main/resources/META-INF/plugin.xml) and [sources package](./src/main/kotlin).
- [ ] Adjust the plugin description in `README` (see [Tips][docs:plugin-description])
- [ ] Review the [Legal Agreements](https://plugins.jetbrains.com/docs/marketplace/legal-agreements.html?from=IJPluginTemplate).
- [ ] [Publish a plugin manually](https://plugins.jetbrains.com/docs/intellij/publishing-plugin.html?from=IJPluginTemplate) for the first time.
- [ ] Set the `PLUGIN_ID` in the above README badges.
- [ ] Set the [Plugin Signing](https://plugins.jetbrains.com/docs/intellij/plugin-signing.html?from=IJPluginTemplate) related [secrets](https://github.com/JetBrains/intellij-platform-plugin-template#environment-variables).
- [ ] Set the [Deployment Token](https://plugins.jetbrains.com/docs/marketplace/plugin-upload.html?from=IJPluginTemplate).
- [ ] Click the <kbd>Watch</kbd> button on the top of the [IntelliJ Platform Plugin Template][template] to be notified about releases containing new features and fixes.

<!-- Plugin description -->
This Fancy IntelliJ Platform Plugin is going to be your implementation of the brilliant ideas that you have.

This specific section is a source for the [plugin.xml](/src/main/resources/META-INF/plugin.xml) file which will be extracted by the [Gradle](/build.gradle.kts) during the build process.

To keep everything working, do not remove `<!-- ... -->` sections. 

## Color palette
```css
.base00 { color: #2b303b; }
.base01 { color: #343d46; }
.base02 { color: #4f5b66; }
.base03 { color: #65737e; }
.base04 { color: #a7adba; }
.base05 { color: #c0c5ce; }
.base06 { color: #dfe1e8; }
.base07 { color: #eff1f5; }
.base08 { color: #bf616a; }
.base09 { color: #d08770; }
.base0A { color: #ebcb8b; }
.base0B { color: #a3be8c; }
.base0C { color: #96b5b4; }
.base0D { color: #8fa1b3; }
.base0E { color: #b48ead; }
.base0F { color: #ab7967; }
```

```css
.base00 { color: #0d2a3b; } /* 深海ブルー */
.base01 { color: #11344d; } /* 深海ブルー - より明るく */
.base02 { color: #004466; } /* クジラブルー */
.base03 { color: #285a75; } /* クジラブルー - より明るく */
.base04 { color: #50798f; } /* クジラブルー - 更に明るく */
.base05 { color: #789caa; } /* クジラブルー - 更に更に明るく */
.base06 { color: #9fbece; } /* クジラブルー - かなり明るく */
.base07 { color: #c3dfe8; } /* クジラブルー - 最も明るく */
.base08 { color: #437c62; } /* Moss */
.base09 { color: #D2691E; } /* Rust */
.base0A { color: #c3bf9f; } /* サンドダラー */
.base0B { color: #8da870; } /* 浅瀬の緑 */
.base0C { color: #206c5a; } /* ダーク海藻グリーン */
.base0D { color: #bcd7d4; } /* シーガラス */
.base0E { color: #17807e; } /* トロピカルウォーターブルー */
.base0F { color: #70877f; } /* シーグリーン */
.base10 { color: #CD5C5C; } /* Coral Reef */
.base11 { color: #7b8794; } /* Pavement Gray */
.base12 { color: #702830; } /* Firebrick3 */
```

## base 16 styling
```
base00 - Default Background
base01 - Lighter Background (Used for status bars, line number and folding marks)
base02 - Selection Background
base03 - Comments, Invisible, Line Highlighting
base04 - Dark Foreground (Used for status bars)
base05 - Default Foreground, Caret, Delimiters, Operators
base06 - Light Foreground (Not often used), Symbols
base07 - Light Background (Not often used)
base08 - Variables, XML Tags, Markup Link Text, Markup Lists, Diff Deleted
base09 - Integers, Boolean, Constants, XML Attributes, Markup Link Url
base0A - Classes, Markup Bold, Search Text Background
base0B - Strings, Inherited Class, Markup Code, Diff Inserted
base0C - Support, Regular Expressions, Escape Characters, Markup Quotes
base0D - Functions, Methods, Attribute IDs, Headings
base0E - Keywords, Storage, Selector, Markup Italic, Diff Changed
base0F - Deprecated, Opening/Closing Embedded Language Tags, e.g. <?php ?>
base10 - Error, Alert
base11 - Disabled code, unused variables
base12 - Further darkened background similar to Coral Reef suitable for dark theme
```
<!-- Plugin description end -->

参考
```css

.base08 { color: #456648; } /* Deep Sea Weed */
.base09 { color: #785A46; } /* Earth Brown */
.base0A { color: #C3A77B; } /* Sand Dune */
.base0B { color: #8D9C6E; } /* Seagrass */
.base0C { color: #627C85; } /* Subtle Wave */
.base0D { color: #7998A1; } /* Ocean Mist */
.base0E { color: #63727A; } /* Zen Stone */
.base0F { color: #5E4B3C; } /* Driftwood */

```

## Installation

- Using the IDE built-in plugin system:
  
  <kbd>Settings/Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>Marketplace</kbd> > <kbd>Search for "intellij-themes-ocean"</kbd> >
  <kbd>Install</kbd>
  
- Manually:

  Download the [latest release](https://github.com/naoyukik/intellij-themes-ocean/releases/latest) and install it manually using
  <kbd>Settings/Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>⚙️</kbd> > <kbd>Install plugin from disk...</kbd>


---
Plugin based on the [IntelliJ Platform Plugin Template][template].

[template]: https://github.com/JetBrains/intellij-platform-plugin-template
[docs:plugin-description]: https://plugins.jetbrains.com/docs/intellij/plugin-user-experience.html#plugin-description-and-presentation
