# Database Queries

## find all customers that live in London. Returns 6 records.
Around the Horn	
B's Beverages	
Consolidated Holdings	
Eastern Connection	
North/South	
Seven Seas Imports	
## find all customers with postal code 1010. Returns 3 customers.
Cactus Comidas para llevar
Océano Atlántico Ltda.
Rancho grande		
## find the phone number for the supplier with the id 11. Should be (010) 9984510.
Heli Süßwaren GmbH & Co. KG
## list orders descending by the order date. The order with date 1997-02-12 should be at the top.
OrderID 10443 is at the top
## find all suppliers who have names longer than 20 characters. You can use `length(SupplierName)` to get the length of the name. Returns 11 records.
New Orleans Cajun Delights
Grandma Kelly's Homestead	
Cooperativa de Quesos 'Las Cabras'	
Specialty Biscuits, Ltd.	
Refrescos Americanas LTDA	
Heli Süßwaren GmbH & Co. KG	
Plutzer Lebensmittelgroßmärkte AG	
Nord-Ost-Fisch Handelsgesellschaft mbH	
Formaggi Fortini s.r.l.	
Aux joyeux ecclésiastiques	
New England Seafood Cannery	
## find all customers that include the word "market" in the name. Should return 4 records.
Bottom-Dollar Marketse	
Great Lakes Food Market	
Save-a-lot Markets	
White Clover Markets	
## add a customer record for _"The Shire"_, the contact name is _"Bilbo Baggins"_ the address is _"1 Hobbit-Hole"_ in _"Bag End"_, postal code _"111"_ and the country is _"Middle Earth"_.

## update _Bilbo Baggins_ record so that the postal code changes to _"11122"_.

## list orders grouped by customer showing the number of orders per customer. _Rattlesnake Canyon Grocery_ should have 7 orders.

## list customers names and the number of orders per customer. Sort the list by number of orders in descending order. _Ernst Handel_ should be at the top with 10 orders followed by _QUICK-Stop_, _Rattlesnake Canyon Grocery_ and _Wartian Herkku_ with 7 orders each.

## list orders grouped by customer's city showing number of orders per city. Returns 58 Records with _Aachen_ showing 2 orders and _Albuquerque_ showing 7 orders.

## delete all users that have no orders. Should delete 17 (or 18 if you haven't deleted the record added) records.
