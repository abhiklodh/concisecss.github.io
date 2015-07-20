# Typography

Concise has a global font-size of **16px** (1em) with a line-height of **1.5** (24px). This is applied to all text within the `<body>` tag. Also, all `<p>` tags receive a bottom-margin of **24px**, the exact same size as our line height.

<p class="note note--preprocessor">You can change the `$base-font-size` variable in the `/helpers/_variables.scss` file to adjust the base font size. In addition, the `$base-font-color` and `$base-link-color` variables will change the font color and link color, respectively.</p>

<div class="preview">
  <p class="preview-heading">Preview</p>

  <p class="preview-body">Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.
  </p>

  <div class="preview-footer">
    <strong>Code</strong>

    `<p>...</p>`
  </div>
</div>

## Font Families

Typography is a key to effective design, so Concise makes it simple to control in your project.

By default, <a href="http://www.linotype.com/en/526/helvetica-family.html?id=526&name=helvetica&viewmode=family&site=&lang=en" target="_blank">Helvetica</a>, with <a href="http://www.fonts.com/font/monotype/arial" target="_blank">Arial</a> as a fallback, is used as the default font for devices.

<p class="note note--preprocessor">You can change the `$base-font-family` variable in the `/helpers/_variables.scss` file to adjust the base font families.</p>

## Emphasis

**Small**

The `<small>` tag and `.small` class can both be used to shrink text to a font size of **12px**. Note that heading elements receive their own font size for nested small elements.

<p class="note note--preprocessor">You can change the `$small-size` variable in the `/helpers/_variables.scss` file to adjust the small font size.</p>

<div class="preview">
  <p class="preview-heading">Preview</p>

  <p class="preview-body">This is a sentence of small text.</p>

  <div class="preview-footer">
    <strong>Code</strong>

    <small>This is a sentence of small text.</small>
  </div>
</div>

**Extra Small**

The `.micro` class can be used to shrink text to a font size of **10px**.

<p class="note note--preprocessor">You can change the `$micro-size` variable in the `/helpers/_variables.scss` file to adjust the micro font size.</p>

<div class="preview">
  <p class="preview-heading">Preview</p>

  <p class="preview-body">This is a sentence of micro text.</p>

  <div class="preview-footer">
    <strong>Code</strong>

    <p class="micro">This is a sentence of micro text.</p>
  </div>
</div>

**Italics**

The `<em>` tag is used for emphasizing text with italics.

<div class="preview">
  <p class="preview-heading">Preview</p>

  <p class="preview-body">This is a sentence with <em>some italics</em> in it.</p>

  <div class="preview-footer">
    <strong>Code</strong>

    This is a sentence with <em>some italics</em> in it.
  </div>
</div>

<p class="note">The `<i>` tag also can be used for emphasizing text in an italic manner, although it is not recommended as `<em>` should be used. However, the `<i>` tag can still be used to define text in an alternative voice or mood.</p>

**Bold**

The `<strong>` tag is used for emphasizing text with a heavier font-weight.

<div class="preview">
  <p class="preview-heading">Preview</p>

  <p class="preview-body">This is a sentence with bold text in it.</p>

  <div class="preview-footer">
    <strong>Code</strong>

    This is a sentence with <strong>bold text</strong> in it.
  </div>
</div>

<p class="note">The `<b>` tag also can be used for emphasizing text in a bold manner, although it is not recommended as `<strong>` should be used. should be used. Per the HTML5 specification, the `<b>` tag should be used as a last resort for formatting text as most HTML5 tags cover its potential uses.</p>
