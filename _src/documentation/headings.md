# Headings

Concise includes all standard HTML headings `<h1>` through `<h6>`. Also included are classes `.h1` through `h6` that match the size of their respective headings, but can be used on any element.

<p class="note note--preprocessor">SASS variables are used for the various heading sizes. You can find these variables at the top of the `/core/layout/_headings.scss` file.</p>

<div class="preview">
  <div class="preview-heading">
    <strong>Preview</strong>
  </div>

  <div class="preview-body">
    <h1>Concise Heading</h1>
    <h2>Concise Heading</h2>
    <h3>Concise Heading</h3>
    <h4>Concise Heading</h4>
    <h5>Concise Heading</h5>
    <h6>Concise Heading</h6>
  </div>

  <div class="preview-footer">
    <strong>Code</strong>

    ```html
      <h1>Heading 1</h1>
      <h2>Heading 2</h2>
      <h3>Heading 3</h3>
      <h4>Heading 4</h4>
      <h5>Heading 5</h5>
      <h6>Heading 6</h6>
    ```
  </div>
</div>

## Sub-Headings

You also can create sub-headings for your headings using the `<small>` tag or the `.small` class. `!important` is included to avoid specificity issues.

<div class="preview">
  <div class="preview-heading">
    <strong>Preview</strong>
  </div>

  <div class="preview-body">
    <h1>Heading 1 <small>This is a sub-heading</small></h1>

    <h2>Heading 2 <small>This is a sub-heading</small></h2>

    <h3>Heading 3 <small>This is a sub-heading</small></h3>

    <h4>Heading 4 <small>This is a sub-heading</small></h4>

    <h5>Heading 5 <small>This is a sub-heading</small></h5>

    <h6>Heading 6 <small>This is a sub-heading</small></h6>
  </div>

  <div class="preview-footer">
    <strong>Code</strong>

    ```html
      <h1>Heading 1 <small>This is a sub-heading</small></h1>
      <h2>Heading 2 <small>This is a sub-heading</small></h2>
      <h3>Heading 3 <small>This is a sub-heading</small></h3>
      <h4>Heading 4 <small>This is a sub-heading</small></h4>
      <h5>Heading 5 <small>This is a sub-heading</small></h5>
      <h6>Heading 6 <small>This is a sub-heading</small></h6>
    ```
  </div>
</div>

## Extra-Large

Sometimes there is a need for headings that are larger than the standard `<h1>` through `<h6>`. Anticipating this need, Concise comes with three classes that can be used to super-size your type.

<div class="preview">
  <div class="preview-heading">
    <strong>Preview</strong>
  </div>

  <div class="preview-body">
    <h3 class="giga">Giga Concise Heading</h3>

    <h3 class="mega">Mega Concise Heading</h3>

    <h3 class="kilo">Kilo Concise Heading</h3>
  </div>

  <div class="preview-footer">
    <strong>Code</strong>

    ```html
      <h3 class="giga">Giga Heading</h3>
      <h3 class="mega">Mega Heading</h3>
      <h3 class="kilo">Kilo Heading</h3>
    ```
  </div>
</div>
