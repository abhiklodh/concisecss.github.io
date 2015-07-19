# Principles

Concise is built on a set of simple but important principles that aid in effective and manageable web design. By understanding these principles, Concise can be used to its full potential, and we can create a better paradigm for using HTML and CSS to build websites.

## Semantics

Concise was built with semantics in mind. Semantics in regard to web design, for those unfamiliar with the term, describes the use of readable and meaningful HTML tags and CSS class names used to build a website.

Meaningful names are those such as `.article-content`. This class name easily explains that this portion of our website is the content of an article. This class name is not too verbose, and provides *meaning* and *context* for our code.

Thanks to the utility classes that Concise provides, we can also very easily style this class so that it fits into our layout. Say we want our articles to take up 8 columns and our sidebar to take up 4. Our HTML could look like:

```html
<div class="column-8">
  Article
</div>

<div class="column-4">
  Sidebar
</div>
```

Or, we could use an included SASS mixin to have this make a little more sense:

```sass
.article {
  @include column(8);
}

.sidebar {
  @include column(4);
}
```

```html
<div class="article">
  Article
</div>

<div class="sidebar">
  Sidebar
</div>
```

While this does add some CSS overhead to your project, it makes a lot more sense than just using the `.column-*` classes, and would be much easier to find inside of your CSS or SASS document.
