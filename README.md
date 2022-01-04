# Telephone Number Validator

freeCodeCamp JavaScript Algorithms and Data Structure project

## Description

Return true if the passed string looks like a valid US phone number.

## Example

```JavaScript
// Telephone Number Validator
const telephoneCheck = (str) => {
  const regex =
    /^[+]?(1\-|1\s|1|\d{3}\-|\d{3}\s|)?((\(\d{3}\))|\d{3})(\-|\s)?(\d{3})(\-|\s)?(\d{4})$/g;
  return str.match(regex) ? true : false;
};

// I/O
telephoneCheck('5555555555'); // true
telephoneCheck('1 555-555-5555'); // true
telephoneCheck('555-5555'); // false

```


