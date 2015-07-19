# Configuration

## Sanitize.css

Concise includes Jonathan Neal's lovely <a href="http://jonathantneal.github.io/sanitize.css/" target="_blank">sanitize.css</a> to help in standardizing styles for common elements across multiple browsers. However, we have adjusted the package to include only what was needed for Concise, so it does not include 100% of the sanitize.css code.

## Disabling Responsiveness

Not interested in the responsive design that comes with Concise by default? Have no fear, disabling responsiveness can be accomplished with a few easy steps.

First, we need to ensure that the following `<meta>` tags are *not* present in our website's `<head>` section.

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="HandheldFriendly" content="True">
<meta name="MobileOptimized" content="320">
```

In your custom CSS files, or in `<style>` tags, you need to set a fixed width for your container element (I'm using 960 pixels as my example):

```css
.container { width: 960px !important; }
```

This overrides the Concise responsive container that is enabled by default. Next, we need to add a single class to the `<body>` tag, that will aid in disabling other responsive aspects of the site:

```html
<body class="non-responsive">
```

Just like that, you have a non-responsive website, and there’s an added bonus. Concise is built so that you can declare any width for your `.container` class, and the grid columns will adjust automatically. Every single column will have a correct width relative to that of the container.
