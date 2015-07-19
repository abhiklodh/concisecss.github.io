# File Organization

## Pre-Compiled Concise

The Concise directory is pretty simple. Here is what you are looking at for the regular distribution download:

```
/css
  concise.css
  concise.min.css
/test
  test.html
```

## Concise Source Code

If you are downloading the SASS package, the folder structure will look like:

<p class="note">All of the files labeled with an underscore are referred to as *partials*. A partial is a file that does not become compiled on its own, but rather, is included in a master file <small>(in this case, it's `concise.scss`)</small> to be compiled.</p>

```
/dist
  /css
    concise.css
    concise.min.css
/src
  /sass
    /addons
      /concise-ui
        /components
          _alerts.scss
          _badges.scss
          _breadcrumbs.scss
          _buttons.scss
          _cards.scss
          _collections.scss
          _dropdowns.scss
          _groups.scss
          _icons.scss
          _labels.scss
          _modals.scss
          _progress.scss
          _spinner.scss
          _tooltips.scss
        _concise-ui.scss
    /core
      /globals
        _functions.scss
        _globals.scss
        _mixins.scss
      /layout
        _base.scss
        _blockquotes.scss
        _buttons.scss
        _forms.scss
        _headings.scss
        _lists.scss
        _print.scss
        _tables.scss
        _type.scss
      /utils
        _atgrid.scss
        _colors.scss
        _conditional-styling.scss
        _helpers.scss
    /custom
      _custom.scss
      _globals.scss
    concise.scss
/test
  test.html
.editorconfig
.gitattributes
.gitignore
LICENSE
README.md
package.json
```
