#### section 1

- succ 8
- min 9 10 - max 10 11

- function have the highest presedence 

- succ 9 + min 5 4 + 1 -> (succ 9) + (min 4 5) + 1

- values in a list should have the same type

- appending (++ operator) two lists together will go through all the elements
 of the first list and may cause problem with large list

- prepend item to the first of list 
  'A' : " SMALL CAT"

- !! operator will the elements of list
 list !! 6, get list[6]

- list containing lists let a = [[1,2,3],[4,5,6],[7,8,9]]

- prepend another list [3,3,3]:a

- comparing two lists will start from the first element, if the operation
 is > and the first elements where equal it will compare the next element

- functions for list `head`, `tail`, `last`, `init`, `length`, `null`, `take`
 `drop`, `minimum`, `maximum` they all take a single list as input

- if a values exists in a list 4 `elem` [1,2,3,4,5]

- make a list from 1 to 20, [1..20], ['a'..'z'], [1,3..30]

- make a declining list [20,19..1]

- using floating point number is not suggested [1.2,1.3..10]

- `cycle` takes a list and make it to an infinite list.
 to make the list finite we can use take 10 (cycle "LOL ")

- set comprehension in mathematics, get the first 10 even number 
 [x*2 | x <- [1..10]]

- get the first 10 even numbers which are greater than 12
 [x*2 | x <- [1..10], x*2 >= 12]

- filter numbers between 50 to 100 which their remainder to 7 is 3
 [x | x <- [50..100], x `mod` 7 == 3]

- a function that replaces each number greater than 10 with "BANG"
  boomBANGS xs = [if x > 10 then "BOOM" else "BANG" | x <- xs, even x]

- our own version of list length' xs = sum [1 | _ <- xs]

- remove lower case from the list 
 removelower xs = [ x | x <- xs, x `elem` ['a'..'z']]

- get the even number of the list from the list of lists
 geteven xss = [[x | x <- xs, even x] | xs <- xss]

- a tuple with two value is called a pair, you can access the first element
 by `fst` and you can access the second element with `snd`.

- the `zip` function takes two lists and makes a pair with them 

- 

