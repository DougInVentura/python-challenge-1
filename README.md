# python-challenge-1
## Assignment 2: Food Truck Ordering Exercise
### Doug Francis
### 12/14/2023

This program presents a food truck menu and allows the user to
first select the menu category (Snacks, Meals, Drinks, or Desserts)
Once the category is selected, the user selects the item in the category (such as Pizza under meals).  They also select the quantity. 

Error checking is used to ensure valid entries. program is in a loop until
the order is completed. Once exception to this, per the assignment instructions was to check for valid entry on quanity selected. User is not notified if the quanity is not valid, instead it defaults to 1 item.

After the order is completed, the user is thanked, then a receipt is presented
to the screen, with the item name, quanity and price.

Finally a total cost is calculated (sum(price * quantity)) accross all of the items they have ordered.