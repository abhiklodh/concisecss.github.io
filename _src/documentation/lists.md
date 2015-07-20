# Lists

## Unordered

Unordered lists are used for items in which order does not matter.

**Default**

<div class="preview">
  <div class="preview-heading">
    <strong>Preview</strong>
  </div>

  <div class="preview-body">
    <ul>
      <li>List Item
        <ul>
          <li>One Level Deep
            <ul>
              <li>Two Levels Deep</li>
            </ul>
          </li>
        </ul>
      </li>
      <li>List Item</li>
      <li>List Item</li>
    </ul>
  </div>

  <div class="preview-footer">
    <strong>Code</strong>

    ```html
      <ul>
        <li>...</li>
      </ul>
    ```
  </div>
</div>

## Ordered

Ordered lists are useful for list items that have a definitive order.

<div class="preview">
  <div class="preview-heading">
    <strong>Preview</strong>
  </div>

  <div class="preview-body">
    <ol>
      <li>List Item
        <ol>
          <li>One Level Deep
            <ol>
              <li>Two Levels Deep</li>
            </ol>
          </li>
        </ol>
      </li>
      <li>List Item</li>
      <li>List Item</li>
    </ol>
  </div>

  <div class="preview-footer">
    <strong>Code</strong>

    ```html
      <ol>
        <li>...</li>
      </ol>
    ```
  </div>
</div>

## Unstyled

A list will have no bullet points or left margin when using the `.list--unstyled` class.

<div class="preview">
  <div class="preview-heading">
    <strong>Preview</strong>
  </div>

  <div class="preview-body">
    <ul class="list--unstyled">
      <li>List Item</li>
      <li>List Item</li>
      <li>List Item</li>
    </ul>
  </div>

  <div class="preview-footer">
    <strong>Code</strong>

    ```html
      <ul class="list--inline">
        <li>...</li>
      </ul>
    ```
  </div>
</div>

## Description

A description list defines terms along with corresponding descriptions.

<div class="preview">
  <div class="preview-heading">
    <strong>Preview</strong>
  </div>

  <div class="preview-body">
    <dl>
      <dt>Coffee</dt>
        <dd>Black hot drink</dd>
      <dt>Milk</dt>
        <dd>White cold drink</dd>
    </dl>
  </div>

  <div class="preview-footer">
    <strong>Code</strong>

    ```html
      <dl>
        <dt>...</dt>
        <dd>...</dd>
      </dl>
    ```
  </div>
</div>
