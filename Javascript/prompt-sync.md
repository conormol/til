# Prompt-Sync

The `prompt-sync` Node module provides an easy method of working wit user input. To use this, Node and NPM have to be installed, and the following command must be run in the terminal to run npm install prompt-sync:

```
const prompt = require('prompt-sync')();
```

## Letting users exit
In order to let the user exit the program, the user must be allowed to send a *SIGNIT* or 'Signal Interrupt' message (using `CTRL-C`). To achieve this, the following code can be added:

```
const prompt = require('prompt-sync')({signit: true});
```

## Working with numbers
Note that numbers are input as a string, and so to treat them as numbers, they need to be converted. This can be done using `Number()`: 
```
const const prompt = require('prompt-sync')({signit: true});

const num = prompt ('input a number: ');
Number(num);
```
