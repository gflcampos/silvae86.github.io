---
layout: page
title: Restaurant
include_in_menu: false
permalink: /teaching/exercises/uml/class/scenarios/restaurant/
crumbtitle: Restaurant
tags: exercises uml
---

## Restaurant

The owner of a small restaurant wants a new information system to store data for all meals consumed there and also to keep a record of ingredients kept in stock. After some research he reached the following requirements list:

- Each ingredient has a name, a measuring unit (e.g. olive oil is measured in liters, while eggs are unit based) and a quantity in stock. There are no two ingredients with the same name.
- Each dish is composed of several ingredients in a certain quantity. An ingredient can, of course, be used in different dishes.
- A dish has an unique name and a numeric identifier.
- There are several tables at the restaurant. Each one of them has an unique numeric identifier and a maximum ammount of people that can be seated there.
- In each meal, several dishes are consumed at a certain table. The same dish can be eaten more than once in the same meal.
- A meal takes place in a certain date and has a start and end time. Each meal has a responsible waiter.
- A waiter has an unique numerical identifier, a name, an address and a phone number.
- In some cases it is important to store information about the client that consumed the meal. A client has a tax identification number, a name and an address.


### Acknowledgement

Credits: [André Restivo](https://web.fe.up.pt/~arestivo/page/exercises/entity-relationship/restaurant/)
