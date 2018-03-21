# breadbox-item

A Polymer Element showing a 'breadbox' (or 'badge') with text and other optional content.

### Example
```html
<breadbox-item text="Hello World">
  <iron-icon icon="clear"></iron-icon>
</breadbox-item>
```

### Styling

`<breadbox-item>` provides the following custom properties and mixins for styling:

Custom property                    | Description        | Default
-----------------------------------|--------------------|----------------------
`--breadbox-item-bg-color`         | Background color   | --paper-grey-300
`--breadbox-item-icon-style-mixin` | Icon style mixin   | none
`--breadbox-item-style-mixin`      | Custom style mixin | none
`--breadbox-item-text-color`       | Text color         | --paper-grey-900

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct

### Demonstration & Documentation

Demonstration and documentation are viewed using [polyserve](https://github.com/PolymerLabs/polyserve):

    npm install -g polyserve
    polyserve

