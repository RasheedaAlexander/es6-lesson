# ES6: Getters and Setters & Template Literals

## Getters & Setters
**Definition**: Getters and setters are used for defining computed properties. A computed property is one that uses a function to get or set an object value.

### Example from ES5
```
var person = {
  name: "Beyonce",
  get name() {
    return this.name;
  },
  set personName(val) {
    this.name = val;
  }
}
```

Then in the console:

```
person.name = "Mrs. Carter"
var bestArtistEver = person.name
console.log(bestArtistEver);
```

### Examples using ES6
```
class Person {
  constructor(name) {
    this._hello = name;
  }
  get personName() {
    return this._hello;
  }
  set personName (newName) {
    this._name = newName;
  }
}
```

Then in the console:

```
let adele = new Person("Adele")
adele.personName
adele.personName = "A-Dawg"
adele.personName
```

### Video
[![video](images/video-getters-setters.png)](https://www.youtube.com/watch?v=nx6DFeNIXlA)

## Template Literals
Template Strings use back-ticks rather than single or double quotes.

They help make the following easier:

* String interpolation
* String concatenation
* Multiline strings
* String substitution

### Example from ES5
```

```

### Examples from ES6
```

```
