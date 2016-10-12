# elastic-client-query-builder

An element which builds an elasticjs query based on the set attributes.

Example:
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
