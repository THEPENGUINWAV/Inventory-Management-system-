# Inventory-Management-system
This is a simple inventory management system, which takes in a predefined dictionary which I have used as an inventory and let's a shopper purchase items to their will , doing necessary changes to the main inventory and also giving a sales report.

The system allows the following functions:

We have a Purchase tab which asks user what they wish to buy with unique ids, which corresponds to a single entry in list.
Products are of two categories and they all have different pricing.You start with 100 of each items and every change you make is reflected in the original (unless you use the first dictionary definition).

We can also give a discount on pricing if the use has a coupon code. SAVE100 gives $100 off and SAVE50 gives $50 off.If you have no coupon code, this part is skipped.

Furthermore, we give the user the details of what they are buying and in what quantity they will buy it , given with the calculated cost aswell.If the user wishes to opt out of shopping after they see the price , they can exit out of the purchase window by inputting "N" in the purchase confirmation prompt.

The Inventory is changed only after a successful purchase is made.The inventory file is stored in a .json format.

Whatever product is sold will generate an entry in the sales record json file for easy updation reevaluation.

Lastly , owners with admin privileges can choose to add to their stock more item. If you don't have the password , you may not be allowed to add inventory and hence skip the entire block of inventory addition.

The project is focused to be a small scale model and does not have certain safety measures. Please be cautious if you wish to use this for your self.



-Dhruv Khatana
