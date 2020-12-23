jquery-masonry-grid
-------------------

Simple, responsive and lightweight Masonry Grid jQuery Plugin.

#### Installation

Add the script before closing the `<body>` tag (make sure you use the right path):
```html
<!-- jQuery -->
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
<!-- Masonry Grid Plugin -->
<script src="js/jquery.masonryGrid.js"></script>
```

#### Usage
There is a demo file `demo/index.html` in the repository you can use as reference.
These options are the default options so this usage would be a little redundant.
```js
<script>
    jQuery(document).ready(function($) {
        $('.my-masonry-grid').masonryGrid({
            'columns': 3,
            'breakpoint': 767
        });
    });
</script>
```
