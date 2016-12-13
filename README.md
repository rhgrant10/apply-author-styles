apply-author-styles
===================

Pull page styles into Polymer custom elements.

This is a fork of the work by `frauben` and `eee-c` for the sole purpose of an updated `bower.json`.

Add `rhgrant10/apply-author-styles` to Bower dependencies:

```
$ bower install --save rhgrant10/apply-author-styles
```

Then import and use the `<apply-author-styles>` tag:

```html
<link rel="import"
      href="../bower_components/apply-author-styles/apply-author-styles.html">
<polymer-element name="x-pizza">
  <template>
    <apply-author-styles></apply-author-styles>
    <!-- ... -->
  </template>
  <script src="x_pizza.js"></script>
</polymer-element>
```

That's all there is to it. Styles defined in the `<head>` of the containing document will now be applied to the Polymer element. Yay!
