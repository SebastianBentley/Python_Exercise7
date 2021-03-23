# Python Exercise 08

## Exercise 1
1. Go to this website: [https://www.komplett.dk/category/21661/gaming/gaming-pc/baerbar](https://www.komplett.dk/category/21661/gaming/gaming-pc/baerbar)
2. Use BeautifulSoup, to select the name and price for the laptops (hint: look for class="product-price" to begin with).
3. Create a mysql table called laptops.
4. Insert the laptop data into the laptops table, using a mysql connector and cursor.

## Exercise 2
1. Create a restful webservice that can respond to the following requests:

| Method | URL              | Response                                             | Description                                     |
|--------|------------------|------------------------------------------------------|-------------------------------------------------|
| GET    | /api/laptops/all | [{"id":1, "name":"ASUS TUF", "price":9999},{},{}...] | Returns all the laptop object from the database |
| POST   | /api/laptops     | POST json: {"name":"Acer", "price":12345             | Adds a new Laptop object to the database        |

## Exercise 3
1. Select the data from the database, using the cursor made in Exercise 1.
2. Make a sorted bar chart of the laptops, where x-axis is names, and y-axis is price.



#### Made by Powerpuff Pigerne & Professor Utonium:
- Michael Ibsen (cph-mi93@cphbusiness.dk)
- Rasmus Grønbek (cph-rg86@cphbusines.dk)
- Sebastian Bentley (cph-sb287@cphbusiness.dk)
- Sebastian Steen Lundby Hansen (cph-sh499@cphbusiness.dk)
