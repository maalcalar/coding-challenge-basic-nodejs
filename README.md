# BASIC NODEJS CHALLENGES

1. Install VsCode "prettier" Plugin 
2. Install the NodeJS Project using the package.json 
3. Happy Hacking!

> Find a solution for any of this challenge using ES6 or greater sintax.


## 1. Anagrams

### Prompt

Create a 'StringChecker' class with a method that takes in two strings as two parameters and return a boolean that indicates whether or not the first string is an anagram of the second string.

### Input

```
(String, String)
```

### Output
```
Boolean
```

### Example
```javascript
StringChecker.method('vino', 'ovni'); // true
StringChecker.method('pero', 'ropa'); // false
StringChecker.method('recorre', 'cerrero'); // true
```

### Tip
- An anagram is another word or phrase formed by rearranging letters of the first word or phrase.


## 2. Balanced Brackets

### Prompt
Create a 'StringChecker' class with a method that takes a string as a parameter containing three types of braces ("{}", "[]", "()") and returns a boolean indicating whether the given string contains a valid nesting of braces.

### Input
```
(String)
```

### Output
```
Boolean
```

### Example
```javascript
StringChecker.method('(([{}])){}[]'); // true
StringChecker.method('[][{)(}]'); // false
```

### Tip
- A string is considered balanced if it has as many opening brackets of a given type as it has closing brackets of that same type. No bracket can be left unmatched. A closing bracket also cannot match a corresponding opening bracket that comes after it. Brackets also cannot overlap each other.


## 3. Armstrong number

### Prompt
Create a 'NumberChecker' class with a method that take a number and returnd wheter or not is an Armstrong number.

### Input
```
(Number)
```

### Output
```
Boolean
```

### Example
```javascript
NumberChecker.method(153); // true (1^3 + 5^3 + 3^3 = 153)
NumberChecker.method(43); // false (4^2 + 3^2 = 25)
```

### Tip
- An Armstrong number is an n-digit number that is equal to the sum of the *nth* powers of its digits. Determine if the input number is an Armstrong number. Return either true or false.