# Tables

## Basic

A basic table without any styling can be created with just the standard `<table>` tag and accompanying elements.

<div class="preview">
  <div class="preview-heading">
    <strong>Preview</strong>
  </div>

  <div class="preview-body">
    <table>
      <thead>
        <tr>
          <th scope="col">#</th>
          <th scope="col">First Name</th>
          <th scope="col">Last Name</th>
        </tr>
      </thead>

      <tbody>
        <tr>
          <td>1</td>
          <td>Keenan</td>
          <td>Payne</td>
        </tr>

        <tr>
          <td>2</td>
          <td>John</td>
          <td>Doe</td>
        </tr>

        <tr>
          <td>3</td>
          <td>Jane</td>
          <td>Doe</td>
        </tr>
      </tbody>
    </table>
  </div>

  <div class="preview-footer">
    <strong>Code</strong>

    ```html
      <table>
         ...
      </table>
    ```
  </div>
</div>

## Responsive Container

When you have a table with a lot of columns, you may not want to hide columns conditionally or shrink them down to the point where they are unreadable. By wrapping a table in the `.table-responsive` class, the size of the table remains the same and a horizontal scroll bar will show up, allowing users to scroll horizontally to view all of the information.

Try resizing the browser and see how the table below changes.

<div class="preview">
  <div class="preview-heading">
    <strong>Preview</strong>
  </div>

  <div class="preview-body">
    <table class="table">
      <thead>
        <tr>
          <th scope="col">#</th>
          <th scope="col">First Name</th>
          <th scope="col">Last Name</th>
        </tr>
      </thead>

      <tbody>
        <tr>
          <td>1</td>
          <td>Keenan</td>
          <td>Payne</td>
        </tr>

        <tr>
          <td>2</td>
          <td>John</td>
          <td>Doe</td>
        </tr>

        <tr>
          <td>3</td>
          <td>Jane</td>
          <td>Doe</td>
        </tr>
      </tbody>
    </table>
  </div>

  <div class="preview-footer">
    <strong>Code</strong>

    ```html
    <div class="table-responsive">
      <table>
         ...
      </table>
    </div>
    ```
  </div>
</div>
