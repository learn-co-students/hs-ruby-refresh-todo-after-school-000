---
tags: todo
language: ruby
level: 2
type: todo
---

## All of the Goats

<img src="https://flatiron.atlassian.net/wiki/download/attachments/15597582/giphy-3.gif?version=1&modificationDate=1400603677636&api=v2">

1. Create a `Goat` class.

{% img https://flatiron.atlassian.net/wiki/download/attachments/15597582/giphy-6.gif?version=1&modificationDate=1400603679545&api=v2 %} 

2. Goats have the following attributes: age(integer), name(string), pokes(integer, default to zero in initalization), milk_in_udders(float), moody(true/false, default to false upon initialization).

3. Create the following actions:
  a. A `poke` method that makes the goat puts "baa" if the number of pokes is less that 3. If the goat has more than 3 pokes, it should puts "BAAAAAAAAA GO AWAY" and set the moody attribute to true. The method should also increment the number of pokes by one.

  b. A `milk` method that reduces the `milk_in_udders` quantity by 50%. It should puts "You have milked _____ ml of milk" replacing the blank with the amount that was milked.

  c. A `feed` method that takes different types of food as an argument. Here's what happens for each type of food:
    + Grass will increase the `milk_in_udders` by 30%
    + Muesli will increase the `milk_in_udders` by 40%
    + Tofurkey will increase the `milk_in_udders` by 25%
    + Any other food will cause the goat to throw up (putsing "BAAAAA"), and decrease the `milk_in_udders` by 10%

Now create an instance of `Goat`, poke it until it gets moody, feed it and milk it. Add any other additional methods you want!