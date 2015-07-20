# Functions &amp; Mixins

Concise leverages the power of SASS to include mixins and functions that help with common tasks.

## Mixins

### clearfix()

This mixin takes no parameters, and is only used to generate CSS that will clear both left and right floats.

## Functions

### unitSize()

Use this function to set sizes with proportions. This can help maintain vertical rhythm, and keep your design consistent.

<div class="table-responsive">
  <table class="table">
    <thead>
      <tr>
        <th scope="col">Parameter</th>
        <th scope="col">Type</th>
        <th scope="col">Description</th>
      </tr>
    </thead>

    <tbody>
      <tr>
        <td><code>$multiplier</code></td>
        <td>String</td>
        <td>Amount to multiply the base unit by (8px by default)</td>
      </tr>

      <tr>
        <td><code>$offset</code></td>
        <td>Number</td>
        <td>A value in pixels which will be added to the result. This can be positive for addition or negative for subtraction (default is 0)</td>
      </tr>

      <tr>
        <td><code>$base</code></td>
        <td>String</td>
        <td>Base font size (default is <code>$font-base-size</code>)</td>
      </tr>
    </tbody>
  </table>
</div>

### pxToEm()

This function converts `px` units to `em` units based off of the base font-size. This is used throughout the framework for calculating font-sizes.

<div class="table-responsive">
  <table class="table">
    <thead>
      <tr>
        <th scope="col">Parameter</th>
        <th scope="col">Type</th>
        <th scope="col">Description</th>
      </tr>
    </thead>

    <tbody>
      <tr>
        <td><code>$px</code></td>
        <td>Number</td>
        <td>The value in pixels to convert</td>
      </tr>

      <tr>
        <td><code>$base</code></td>
        <td>Number</td>
        <td>The base font-size used to calculate <code>em</code> units</td>
      </tr>
    </tbody>
  </table>
</div>

### getColor()

Using this function, you can easily retrieve colors from the `$colors` map and use them throughout your design.

<div class="table-responsive">
  <table class="table">
    <thead>
      <tr>
        <th scope="col">Parameter</th>
        <th scope="col">Type</th>
        <th scope="col">Description</th>
      </tr>
    </thead>

    <tbody>
      <tr>
        <td><code>$color</code></td>
        <td>String</td>
        <td>The name of the color to retrieve</td>
      </tr>

      <tr>
        <td><code>$value</code></td>
        <td>Color</td>
        <td>The shade of the color to retrieve</td>
      </tr>
    </tbody>
  </table>
</div>
