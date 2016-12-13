# elastic-client-query-builder

A Polymer Element which builds an elasticjs query based on the set attributes.

### Example
```html
<elastic-client-query-builder
  type: "terms"
  fields: '"myField"'
  values: '["value1","value2"]'
  ejs-query: "{{ejsQuery}}">
</elastic-client-query-builder>
```

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

