# Forms

This is a basic form composed of the <form> tag containing various `<label>,` `<input>,` `<select>` and `<textarea>` fields.

Each label and input pair are wrapped in a `<p>` tag that adds top margin and keeps our respective labels and inputs in their own block so no content wraps around them.

<div class="preview">
  <div class="preview-heading">
    <strong>Preview</strong>
  </div>

  <div class="preview-body">
    <form>
     <p>
       <label for="firstname">First Name:</label>
       <input type="text" id="firstname" placeholder="John">
       <p class="input--help">Here is some help text</p>
     </p>

     <p>
       <label for="lastname">Last Name:</label>
       <input type="text" id="lastname" placeholder="Doe (readonly)" class="input--small" readonly>
     </p>

     <p>
       <label for="success">Success Input:</label>
       <input type="text" id="success" placeholder="Success" class="input--success">
     </p>

     <p>
       <label for="warning">Warning Input:</label>
       <input type="text" id="warning" placeholder="Warning" class="input--warning">
     </p>

     <p>
       <label for="error">Error Input:</label>
       <input type="text" id="error" placeholder="Error" class="input--error">
     </p>

     <p>
       <label for="email">Email:</label>
       <input id="email" type="email" name="email" class="input--flat" placeholder="john_doe@example.com">
     </p>

     <p>
       <label for="website">Website:</label>
       <input id="website" type="text" name="website" class="input--large" placeholder="http://example.com" disabled>
     </p>

     <p>
       <label>Gender:</label>
       <input id="male" type="radio" name="gender" value="Male"> <label for="male">Male</label> <br>
       <input id="female" type="radio" name="gender" value="Female"> <label for="female">Female</label>
     </p>

     <p>
       <label>Reason for contact:</label>
       <input id="message" type="checkbox" name="gender" value="Male"> <label for="message">Message</label> <br>
       <input id="quote" type="checkbox" name="gender" value="Female"> <label for="quote">Quote</label>
     </p>

     <p>
       <select>
         <option name="inquiry">Inquiry</option>
         <option name="inquiry">Inquiry</option>
         <option name="inquiry">Inquiry</option>
       </select>
     </p>

     <p>
       <select multiple>
         <option>1</option>
         <option>2</option>
         <option>3</option>
         <option>4</option>
         <option>5</option>
       </select>
     </p>

     <p>
       <input type="range" min="0" max="100">
     </p>

     <p>
       <input type="date" class="datepicker">
     </p>

     <p>
       <label for="message-2">Message:</label>
       <textarea id="message-2" name="message" rows="6"></textarea>
     </p>

     <input type="submit" value="Submit" class="button">
    </form>
  </div>

  <div class="preview-footer">
    <strong>Code</strong>

    ```html
      <form>
         <p>
           <label for="firstname">First Name:</label>
           <input type="text" id="firstname" placeholder="John">
           <p class="input--help">Here is some help text</p>
         </p>

         <p>
           <label for="lastname">Last Name:</label>
           <input type="text" id="lastname" placeholder="Doe (readonly)" class="input--small" readonly>
         </p>

         <p>
           <label for="success">Success Input:</label>
           <input type="text" id="success" placeholder="Success" class="input--success">
         </p>

         <p>
           <label for="warning">Warning Input:</label>
           <input type="text" id="warning" placeholder="Warning" class="input--warning">
         </p>

         <p>
           <label for="error">Error Input:</label>
           <input type="text" id="error" placeholder="Error" class="input--error">
         </p>

         <p>
           <label for="email">Email:</label>
           <input id="email" type="email" name="email" class="input--flat" placeholder="john_doe@example.com">
         </p>

         <p>
           <label for="website">Website:</label>
           <input id="website" type="text" name="website" class="input--large" placeholder="http://example.com" disabled>
         </p>

         <p>
           <label>Gender:</label>
           <input id="male" type="radio" name="gender" value="Male"> <label for="male">Male</label> <br>
           <input id="female" type="radio" name="gender" value="Female"> <label for="female">Female</label>
         </p>

         <p>
           <label>Reason for contact:</label>
           <input id="message" type="checkbox" name="gender" value="Male"> <label for="message">Message</label> <br>
           <input id="quote" type="checkbox" name="gender" value="Female"> <label for="quote">Quote</label>
         </p>

         <p>
           <select>
             <option name="inquiry">Inquiry</option>
             <option name="inquiry">Inquiry</option>
             <option name="inquiry">Inquiry</option>
           </select>
         </p>

         <p>
           <select multiple>
             <option>1</option>
             <option>2</option>
             <option>3</option>
             <option>4</option>
             <option>5</option>
           </select>
         </p>

         <p>
           <input type="range" min="0" max="100">
         </p>

         <p>
           <input type="date" class="datepicker">
         </p>

         <p>
           <label for="message-2">Message:</label>
           <textarea id="message-2" name="message" rows="6"></textarea>
         </p>


         <fieldset>
           <legend>Files</legend>

           <input type="file">
         </fieldset>


         <input type="submit" value="Submit" class="button">
        </form>
    ```
  </div>
</div>

Fieldset

Wrapping your form content with a `<fieldset>` tag allows you to group related elements inside of your form. Adding the `<legend>` tag allows you to denote each section with a small heading.

<div class="preview">
  <div class="preview-heading">
    <strong>Preview</strong>
  </div>

  <div class="preview-body">
    <form method="post">
      <fieldset>
        <legend>User Information</legend>

        <div class="form-item">
          <label for="name">Name:</label>
          <input type="text" name="name" placeholder="John Doe" />
        </div>

        <div class="form-item">
          <label for="email">Email:</label>
          <input type="email" name="email" placeholder="john_doe@example.com" />
        </div>
      </fieldset>
    </form>
  </div>

  <div class="preview-footer">
    <strong>Code</strong>

    ```html
      <form>
        <fieldset>
          <legend>...</legend>
        </fieldset>
      </form>
    ```
  </div>
</div>

## Inline

Adding the class `.form-inline` to your `<form>` element allows you to display your form elements in an inline fashion. By default, the `.form-inline` class will give each `<label>` element a width of **100px**.

<div class="preview">
  <div class="preview-heading">
    <strong>Preview</strong>
  </div>

  <div class="preview-body">
    <form method="post" class="form-inline">
      <div class="form-item">
        <label for="name">Name:</label>
        <input type="text" name="name" placeholder="John Doe" />
      </div>

      <div class="form-item">
        <label for="email">Email:</label>
        <input type="email" name="email" placeholder="john_doe@example.com" />
      </div>
    </form>
  </div>

  <div class="preview-footer">
    <strong>Code</strong>

    ```html
      <form class="form--inline">
        ...
      </form>
    ```
  </div>
</div>

## Fieldset

Wrapping your form content with a `<fieldset>` tag allows you to group related elements inside of your form. Adding the `<legend>` tag allows you to denote each section with a small heading.

<div class="preview">
  <div class="preview-heading">
    <strong>Preview</strong>
  </div>

  <div class="preview-body">
    <form method="post">
      <fieldset>
        <legend>User Information</legend>

        <div class="form-item">
          <label for="name">Name:</label>
          <input type="text" name="name" placeholder="John Doe" />
        </div>

        <div class="form-item">
          <label for="email">Email:</label>
          <input type="email" name="email" placeholder="john_doe@example.com" />
        </div>
      </fieldset>
    </form>
  </div>

  <div class="preview-footer">
    <strong>Code</strong>

    ```html
      <form>
        <fieldset>
          <legend>...</legend>
        </fieldset>
      </form>
    ```
  </div>
</div>

## Input Modifiers
