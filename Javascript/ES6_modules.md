# ES6 Modules

To export functions from a javascript program, use the following syntax:
```
export { functionA, functionB };
```

To import functions:
```
import ( functionA, functionB } from '../modules/functions.js';
```

## Renaming functions:

To rename a function after its been imported:
```
import { functionA as function1} from '../modules/functions.js';
```

# Default Imports and Exports

We can also import an export a single value to represent the entire module called the _Default Export_ :
```
const resources = {
  valueA,
  valueB
}
export { resources as default };
```

To import the object, the following syntax is used. Note that the values inside the object cannot be extracted until after the object is imported:
```
import resources from '../modules/functions.js';
```
