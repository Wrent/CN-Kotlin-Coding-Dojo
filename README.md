# CN-Kotlin-Coding-Dojo

Related slides: https://docs.google.com/presentation/d/1XroLi5tFzLi3brN79hqtX_Hxhuvy_QRD0Uj7xPWvH7g/edit?usp=sharing

Kata: http://codingdojo.org/kata/Lags/

## Problem description

Our company owns just one plane, which our customers can rent for their needs. Every day, we receive a list of requests for plane rental for that day.

These requests come in this format:
`CUSTOMER_ID RENTAL_START_TIME RENTAL_DURATION RENTAL_PRICE`

An example of such request is `AF514 0 5 10`, which means, that customer `AF514` wants the plane from midnight (`0`) for `5` hours and is willing to pay `10` thousand dollars for it.

A list of requests might look like this:
```
AF514 0 5 10
CO5 3 7 14
AF515 5 9 7
BA01 6 9 8
```

The solution for this example is combination of `AF514` and `BA01` for a total price of `18` thousand.
