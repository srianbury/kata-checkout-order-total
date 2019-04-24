Items Object
fields:
  name (string)
  price (number)
  weight (number) (if applicable)
  weightedItem (boolean)
  markdown (number)
  special (?) i.e. Buy N items get M at %X off." For example, "Buy 1 get 1 free" or "Buy 2 get 1 half off."
  special (?) i.e. "N for $X." For example, "3 for $5.00"
  special (?) i.e. "Buy N, get M of equal or lesser value for %X off" on weighted items.
  specialLimit (number) i.e "buy 2 get 1 free, limit 6" would prevent getting a third free item.
  
methods:
  get price (number)
  

Grocery List Obeject
fields:
  list of items
  total price

methods:
  remove item (and update price at the same time)
  

Inventory Object
  List of Items
  Need to be able to create, and update items in the inventory


Need some sort of in memory object to store the prices, specials, etc for items.

Use a dictionary to keep track of items and their quantity
