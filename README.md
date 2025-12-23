# Sigment NG

Sigment NG is a variant of Sigment — **no global helpers**, all HTML elements are imported explicitly. Ideal for developers who want a clean, modular setup without polluting the global scope.

## Version

v1.3.4

## Usage

You can import it directly from the CDN (or GitHub Pages):

```html
<script type="module">
  import { div, span } from "https://cdn.jsdelivr.net/gh/sigmentjs/sigment-ng@1.3.4/dist/index.js";

  document.body.append(
    div(span("Hello Sigment NG v1.3.4!"))
  );
</script>
