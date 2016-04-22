# Getting-Started
# Constructor functions / Classes

How to create a Car & Ferry!? :-|

Let's look at functions...

---

# What is a function?

* An operation that performs an action and returns the results.

* An operation that takes parameters, perform an action using the parameters and then return a result.

* can have a name

---

# Function examples

> Create a function that takes a sentence and return the number of words in the sentence.

Create the function like this:

```javascript
var wordCount = function(sentence){
    if(!sentence){
        return 0;
    }
    var wordsInSentence = sentence.split(" ");
    return wordsInSentence.length;
}
```

Call the function like this:

```javascript
var count = wordCount("The fox jumps over the fence");
console.log(count);
```
---
