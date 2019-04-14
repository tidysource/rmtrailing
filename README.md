# rmTrailing
Removes trailing substring.

### How to use
#### Prerequisite
None

### Example
```javascript
var slash = '/';

rmTrailing('hello/world/', slash); //'hello/world',
rmTrailing('hello/world//', slash); //'hello/world'
rmTrailing('hello/world', slash) //'hello/world'
rmTrailing('///', slash); //''
rmTrailing('', slash) //''
```

