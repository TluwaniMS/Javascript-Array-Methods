# Javascript-Array-Methods

* `concat()`:

The `concat()` method is used to join two array and return only one

```
const firstFiveNumbers = [1,2,3,4,5]

const secondFiveNumbers = [6,7,8,9,10]

const fullTenNumbers = firstFiveNumbers.concat(secondFiveNumbers)

console.log(fullTenNumbers)
///Will print:
[1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
```

* `indexOf()`:

The `indexOf()` method is used to identify the index of an element in an array

* `includes()`:

The `includes()` method is used to check if an array includes a specified element

```
const numbersArray = [1,2,3,4,5]

const includesTheNumberSeven = numbersArray.includes(7)

const includesTheNumberTwo = numbersArray.includes(2)

console.log(includesTheNumberSeven)
///Will print:
false

console.log(includesTheNumberTwo)
///Will print:
true
```

* `join()`:

The `join()` method is used to join all the elements in an array and return them as a single string

* `push()`:

The `push()` method is used to add new elements to the end of an array

* `splice()`:

The `splice()` method is used to either add or remove elements from an array
