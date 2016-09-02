# ES6: Getters and Setters & Template Literals

## Getters & Setters
**Definition**: Getters and setters are used for defining computed properties. A computed property is one that uses a function to get or set an object value.

### Example from ES5
```

```

### Examples using ES6
```
class Person {
  constructor(name) {
    this._hello = name;
  }
  get name() {
    return this._hello;
  }
  set name (newName) {
    this._name = newName;
    console.log(this._hello + " is set";)
  }
}
```

## Template Literals
Template Strings use back-ticks rather than single or double quotes.

They help make the following easier:

* String interpolation
* String concatenation
* Multiline strings
* Formatting strings (can use both '' and "" without worrying about breaking code)
