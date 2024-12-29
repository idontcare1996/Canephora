<img src="https://github.com/idontcare1996/Canephora/blob/main/res/logo/logo_with_text_svg.svg?raw=true"
     alt="Canephora Logo by Carlos Oliveira" height="128" width="100%">

<img src="https://github.com/idontcare1996/Canephora/blob/main/res/logo/logo_svg.svg?raw=true" alt="Canephora Logo by Carlos Oliveira" height="32" align="right">

# Canephora

A Web Platform to track coffee usage and purchase in an office setting.

<img src="https://github.com/idontcare1996/Canephora/blob/main/res/logo/logo_svg.svg?raw=true" alt="Canephora Logo by Carlos Oliveira" height="32" align="right">

## Features

* Track coffee consumption in an office setting:
  * by User
  * by Coffee Type
* Track each User's:
  * Coffee consumption (filtering by type)
  * Payment History
  * Tally balance
* Automatically notify Coffee Inventory Manager regarding low stocks of Coffee (filtering by type)

<img src="https://github.com/idontcare1996/Canephora/blob/main/res/logo/logo_svg.svg?raw=true" alt="Canephora Logo by Carlos Oliveira" height="32" align="right">

## Motivation

In the office where I work, we have a capsule coffee machine.
Each capsule has a fixed value, and we use an honor system to pay for each capsule consumed.
Sometimes, this value is paid for when the machine is used, by depositing said fixed value in a small cardboard box.
Other times, a mark is added to a tally above the coffee machine.
Either way, the payment still requires physical currency (cash).  
This process raises a few questions:

* How do we keep a reliable tally of coffees?
  * Users sometimes forget if they added a tally before/after having their coffee.
* How do I know how much money I owe at the moment?
  * Counting the tally and multiplying by the fixed value is cumbersome.
* How much debt should be liquidated such that the least ammount of currency is used?
  * If the fixed value is 0.30EUR, then liquidating 100 coffees should be easily done with a 10EUR bank note. In this case, if the coffee tally is at 99 coffees, it's better to wait for the 100th coffee.

I've picked the name Canephora from the [ _Coffea Canephora_](https://en.wikipedia.org/wiki/Coffea_canephora) coffee plant specie, given the project's association with coffee.
