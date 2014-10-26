[![Build Status](https://travis-ci.org/lefoy/cyanide-theme.svg?branch=master)](https://travis-ci.org/lefoy/cyanide-theme) [![Bountysource](https://www.bountysource.com/badge/tracker?tracker_id=1612287)](https://www.bountysource.com/trackers/1612287-cyanide-theme?utm_source=1612287&utm_medium=shield&utm_campaign=TRACKER_BADGE) [![Gittip](http://img.shields.io/gittip/lefoy.svg)](https://www.gittip.com/lefoy/) [![License](http://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/lefoy/cyanide-theme/blob/master/LICENSE) [![Semver](http://img.shields.io/badge/semver-2.0.0-blue.svg)](http://semver.org/spec/v2.0.0.html)

Cyanide Theme for Sublime Text
------------------------------------------------------------------------

A minimal dark theme for Sublime Text 3.

**NEW: [Monocyanide Colorscheme](#monocyanide-colorscheme)**
**NEW: [Sidebar file type icons](#sidebar-file-type-icons)**
**NEW: [Cyanide Theme Builder](#cyanide-theme-builder)**

![Default Theme Screenshot](http://i.imgur.com/NOOomrQ.png)

![Acid Theme Screenshot](http://i.imgur.com/snmvuB4.png)

![Contrasted UI Screenshot](http://i.imgur.com/cfYkL92.png)

Installation
------------------------------------------------------------------------

### Package Manager

Install the theme with the [Command Palette](http://sublime-text-unofficial-documentation.readthedocs.org/en/latest/reference/command_palette.html) and update your `Settings - User` file:

```json
    "color_scheme": "Packages/Theme - Cyanide/Cyanide.tmTheme",
    "theme": "Cyanide.sublime-theme"
```

### Manual

Clone Cyanide Theme into your `packages` folder. Make sure the foldername is `Theme - Cyanide`:

```shell
    cd ~/"Library/Application Support/Sublime Text 3/Packages/"
    git clone git@github.com:lefoy/cyanide-theme.git 'Theme - Cyanide'
```

If you are on Windows, instead run:

```shell
    cd %AppData%/Sublime Text 3/Packages/
    git clone git@github.com:lefoy/cyanide-theme.git 'Theme - Cyanide'
```

Update your `Settings - User` file to activate the theme:

```json
    "color_scheme": "Packages/Theme - Cyanide/Cyanide.tmTheme",
    "theme": "Cyanide.sublime-theme"
```

Themes
------------------------------------------------------------------------

### Monocyanide Colorscheme

If you like [Monokai Extended](https://github.com/jonschlinkert/sublime-monokai-extended), there's a colorscheme called [Monocyanide](https://github.com/Centril/sublime-monocyanide-colorscheme) that was developed specifically for Cyanide. It works with any of the themes.

```json
    "color_scheme": "Packages/Theme - Cyanide/Monocyanide ColorScheme.tmTheme",
```

![Monocyanide screenshot](http://i.imgur.com/GbB80Aj.png)

@TODO @lefoy: add correct picture with same source as the themes.

### Acid theme

```json
    "color_scheme": "Packages/Theme - Cyanide/Cyanide - Acid.tmTheme",
    "theme": "Cyanide - Acid.sublime-theme"
```

![Acid screenshot](http://i.imgur.com/GbB80Aj.png)

### Alert theme

```json
    "color_scheme": "Packages/Theme - Cyanide/Cyanide - Alert.tmTheme",
    "theme": "Cyanide - Alert.sublime-theme"
```

![Alert screenshot](http://i.imgur.com/fSXNPYH.png)

### Golden theme

```json
    "color_scheme": "Packages/Theme - Cyanide/Cyanide - Golden.tmTheme",
    "theme": "Cyanide - Golden.sublime-theme"
```

![Golden screenshot](http://i.imgur.com/XpNt7rM.png)

### Love theme

```json
    "color_scheme": "Packages/Theme - Cyanide/Cyanide - Love.tmTheme",
    "theme": "Cyanide - Love.sublime-theme"
```

![Love screenshot](http://i.imgur.com/cJPqBtT.png)

### Mint theme

```json
    "color_scheme": "Packages/Theme - Cyanide/Cyanide - Mint.tmTheme",
    "theme": "Cyanide - Mint.sublime-theme"
```

![Mint screenshot](http://i.imgur.com/9PkgNGu.png)

### Purple theme

```json
    "color_scheme": "Packages/Theme - Cyanide/Cyanide - Purple.tmTheme",
    "theme": "Cyanide - Purple.sublime-theme"
```

![Purple screenshot](http://i.imgur.com/YT1QGvH.png)

### Salmon theme

```json
    "color_scheme": "Packages/Theme - Cyanide/Cyanide - Salmon.tmTheme",
    "theme": "Cyanide - Salmon.sublime-theme"
```

![Salmon screenshot](http://i.imgur.com/1SO5oms.png)

### Sky theme

```json
    "color_scheme": "Packages/Theme - Cyanide/Cyanide - Sky.tmTheme",
    "theme": "Cyanide - Sky.sublime-theme"
```

![Sky screenshot](http://i.imgur.com/L8egKdc.png)

### Wood theme

```json
    "color_scheme": "Packages/Theme - Cyanide/Cyanide - Wood.tmTheme",
    "theme": "Cyanide - Wood.sublime-theme"
```

![Wood screenshot](http://i.imgur.com/zTc44p7.png)


Settings
------------------------------------------------------------------------

These settings go into `Sublime Text -> Preferences -> Settings - User`.

### Sidebar file type icons

Sublime Text 3 added sidebar icons. Thanks to a great contribution by [Centril](https://github.com/Centril), now also supported in Cyanide!

```json
"icon_file_type_enable": true
```

![Sidebar file type icons](http://i.imgur.com/tRszn4V.png)

### Centurion sidebar folder icons

Sidebar folder icons from the Centurion theme.

```json
"centurion_folder_icons": true
```

![Sidebar folder icons](http://i.imgur.com/QVwmrGh.png)

### Afterglow sidebar folder icons

Sidebar folder icons from the Afterglow theme.

```json
"afterglow_folder_icons": true
```

![Sidebar folder icons](http://i.imgur.com/Ov5hnv2.png)

### Spacefunk sidebar folder icons

Sidebar folder icons from the Spacefunk theme.

```json
"spacefunk_folder_icons": true
```

![Sidebar folder icons](http://i.imgur.com/Xz2FqEG.png)

### Tabs height

Vary tab height with either `tabs_medium` or `tabs_large`.

```json
"tabs_medium": true
```

or

```json
"tabs_large": true
```

![Tabs height](http://i.imgur.com/0NCrXVF.png)

### Contrasted UI

Increased contrast for better legibility.

```json
"contrasted_sidebar": true,
"contrasted_tabs": true,
"contrasted_quick_panel": true
```

![Contrasted UI](http://i.imgur.com/cfYkL92.png)

Or use a lighter alternative:

```json
"contrasted_light_sidebar": true,
"contrasted_light_tabs": true,
"contrasted_light_quick_panel": true
```

## Custom UI font

Change the UI font:

```json
"ubuntu_mono_ui": true // Ubuntu Mono UI font
"monaco_ui": true      // Monaco UI font
"inconsolata_ui": true // Inconsolata UI font
```

## Large scrollbars

Increased scrollbars size for better control.

```json
"large_scroll_bars": true
```

![Large scrollbars](http://i.imgur.com/wfmZdzx.png)

## Cyanide Theme Builder

*You must install the Cyanide Theme manually if you want to use the Cyanide Theme Builder.*

Create your own custom Cyanide Theme with the Theme Builder. If you don't have [grunt](http://gruntjs.com/) installed, do that first.

Go to your Cyanide Theme folder and run:

```shell
npm install
```

Edit the `colors.json` file to add your own custom color.
Edit the `languages.json` file to add your own custom sidebar icon. Match every new entry with images named `file_type_{icon}.png` (dimensions: `16x16`) and `file_type_{icon}@2x.png` (dimensions: `32x32`) in the icons/ directory.

Save the file, and run:

```shell
grunt build
```

Your new theme is generated. Update the Sublime Text settings to use it.

The tasks that are available are:
```shell
grunt
    build       # Does all of the below.
    themes      # Builds the theme files, do this when colors.json is updated.
    languages   # Builds sidebar icon bindings and dummy syntax highlighting.
    monocyanide # Pulls the latest version of Monocyanide from its repo.
```

## Known issues

### Ubuntu Mono UI cuts off the tabs font

![Screenshot - Ubuntu Mono UI cuts off the tabs font](http://i.imgur.com/jdKUPoE.png)

Unfortunatly, this is a Sublime Text bug. As a work-around, use the `"small_ui_font": true` setting. If this doesn't fix it, please file a new issue on GitHub.

## Plugins support

The following Sublime Text plugins are currently supported by Cyanide Theme:

* [GitGutter](https://sublime.wbond.net/packages/GitGutter)
* [SublimeLinter3](https://github.com/SublimeLinter/SublimeLinter3)

<!--* [PlainTasks](https://sublime.wbond.net/packages/PlainTasks)-->
<!--* [FileBrowser](https://sublime.wbond.net/packages/FileBrowser)-->

Acknowledgements
------------------------------------------------------------------------

This theme is based on [Centurion](https://github.com/allanhortle/Centurion), [Afterglow](http://yabatadesign.github.io/afterglow-theme/), [Spacefunk](https://github.com/Twiebie/ST-Spacefunk) and [Seti_UI](https://github.com/ctf0/Seti_ST3).

Thanks to [@Centril](https://github.com/Centril), [@pds2k12](https://github.com/pds2k12), [@hraban](https://github.com/hraban), [@renkun-ken](https://github.com/renkun-ken) and [@wfalkwallace](https://github.com/wfalkwallace) for helping me with bug reports and suggestions.

Like this theme? I'd love to hear! Contact me on Twitter ([@louisetiennefoy](https://twitter.com/louisetiennefoy)).
