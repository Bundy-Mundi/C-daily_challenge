## C++ Daily Challenge !!

### 1. Chocolate Dilemma (Level:Easy)

Two sisters are eating chocolate, whose pieces are represented as subarrays of [l x w].

Write a function that returns true if the total area of chocolate is the same for each sister.

#### To illustrate:

    testFairness([[4, 3], [2, 4], [1, 2]],
    [[6, 2], [4, 2], [1, 1], [1, 1]])
    ➞ true 

    // Agatha's pieces: [4, 3], [2, 4], [1, 2]
    // Bertha's pieces: [6, 2], [4, 2], [1, 1], [1, 1]

    // Total area of Agatha's chocolate
    // 4x3 + 2x4 + 1x2 = 12 + 8 + 2 = 22

    // Total area of Bertha's chocolate is:
    // 6x2 + 4x2 + 1x1 + 1x1 = 12 + 8 + 1 + 1 = 22

#### Examples:
    testFairness([[1, 2], [2, 1]], [[2, 2]]) ➞ true

    testFairness([[1, 2], [2, 1]], [[2, 2], [4, 4]]) ➞ false

    testFairness([[2, 2], [2, 2], [2, 2], [2, 2]], [[4, 4]]) ➞ true

    testFairness([[1, 5], [6, 3], [1, 1]], [[7, 1], [2, 2], [1, 1]]) ➞ false

> [Answer](https://edabit.com/challenge/Ka63T5ZzmEdxZSrBX)

### 2. Reverse the Order of a String(Level:Easy)

Create a function that takes a string as its argument and returns the string in reversed order.

#### Examples:
    reverse("Hello World") ➞ "dlroW olleH"

    reverse("The quick brown fox.") ➞ ".xof nworb kciuq ehT"

    reverse("Edabit is really helpful!") ➞ "!lufpleh yllaer si tibadE"

#### Notes:

You can expect a valid string for all test cases.

> [Answer](https://edabit.com/challenge/gYxDahmv8CbWmiThc)

### 3. Valid Zip Code(Level:Easy)

Zip codes consist of 5 consecutive digits. Given a string, write a function to determine whether the input is a valid zip code. A valid zip code is as follows:

* Must only contain numbers (no non-digits allowed).
* Must not contain any spaces.
* Must not be greater than 5 digits in length.

#### Examples:
    isValid("59001") ➞ true

    isValid("853a7") ➞ false

    isValid("732 32") ➞ false

    isValid("393939") ➞ false

> [Answer](https://edabit.com/challenge/ATK3fdWeyPzN8Xnka)

### 4. State Names and Abbreviations

Create a function that filters out an array of state names into two categories based on the second parameter.

1. Abbreviations <code>abb</code>

2. Full names <code>full</code>

#### Examples:

    filterStateNames(["Arizona", "CA", "NY", "Nevada"], "abb")
    ➞ ["CA", "NY"]

    filterStateNames(["Arizona", "CA", "NY", "Nevada"], "full")
    ➞ ["Arizona", "Nevada"]

    filterStateNames(["MT", "NJ", "TX", "ID", "IL"], "abb")
    ➞ ["MT", "NJ", "TX", "ID", "IL"]

    filterStateNames(["MT", "NJ", "TX", "ID", "IL"], "full")
    ➞ []

> [Answer](https://edabit.com/challenge/9ugiNEhBmxSyDSPMW)

## Resources:

#### [Questions Are From (ClickMe)](https://edabit.com/challenges/cpp)