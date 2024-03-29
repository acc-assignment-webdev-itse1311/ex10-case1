
# NP HTML5, CSS3, and JavaScript 6e
# Tutorial 10, Case Problem 1


### Instruction
```
1.  Use your editor to open the tc_cart_txt.html, tc_cart_txt.js and tc_order_txt.js files from the html10 c case1 folder. Enter your name and the date in the comment section of each file, and save them as tc_cart.html, tc_cart.js and tc_order.js respectively.
2.  Go to the tc_cart.html file in your editor. Directly above the closing </head> tag, insert script elements to link the page to the tc_order.js and tc_cart.js files in that order. Defer the loading and running of both script files until after the page has loaded.
3.  Scroll down the file and directly below the h1 heading titled "Shopping Cart" insert a div element with the ID cart.	
4.  Save your changes to the file and go to the tc_order.js file in your editor.
5.  Within the tc_order.js file, you will create arrays containing information on a sample customer order. Create an array named item that will contain the ID numbers of the items purchased by the customer. Add the following four item numbers to the array: 10582, 23015, 41807, and 10041.	
6.  Create an array named itemDescription containing the following item descriptions:
    •  1975 Green Bay Packers Football (signed), Item 10582
    •  Tom Landry 1955 Football Card (unsigned), Item 23015
    •  1916 Army-Navy Game, Framed Photo (signed), Item 41807
    •  Protective Card Sheets, Item 10041
7.  Create an array named itemPrice containing the following item prices: 149.93, 89.98, 334.93, and 22.67.
8.  Create an array named itemQty containing the following quantities that the customer ordered of each item: 1, 1, 1, and 4.
9.  Save your changes to the file, and then open the tc_cart.js file in your editor.
10.  In your script, you will calculate a running total of the cost of the order. Declare a variable named ordertotal and set its initial value to 0.
11.  Declare a variable named cartHTML that will contain the HTML code for the contents of the shopping cart, which will be displayed as a table. Set its initial value to the text string: <table> <tr> <th>Item</th><th>Description</th><th>Price</th><th>Qty</th><th>Total</th> </tr>
12.  Create a for loop that loops through the entries in the item array. Each time through the loop, execute the commands described in Steps a through e.
     a. Add the following HTML code to the value of the cartHTML variable <tr> <td><img src='tc_item.png' alt='item' /></td> where item is the current value from the item array.
     b.  Add the following HTML code to the cartHTML variable to display the description, price, and quantity ordered of the item <td>description</td> <td>$price</td> <td>guantity</td> where description is the current value from the itemDescription array, price is the current value from the itemPrice array preceded by a $ symbol, and quantity is the current value from the itemQty array.
     c.  Declare a variable named itemCost equal to the price value multiplied by the quantity value for the current item.
     d.  Add the following HTML code to the cartHTML variable to display the cost for the item(s) ordered, completing the table row <td>$cost</td></tr> where cost is the value of the itemCost variable, preceded by a $ symbol.
     e.  Add the value of the itemCost variable to the orderTotal variable to keep a running total of the total cost of the customer order.	
13.  After the for loop has completed, add the following HTML code to the value of the cartHTML variable, completing the shopping cart table <tr> <td colspan='4'>Subtotal</td> <td>$total</td> </tr> </table> where total is the value of the orderTotal variable, preceded by a $ symbol.
14.  Apply the cartHTML value to the inner HTML of the div element with the ID cart.
15.  Document your script file with appropriate comments, and then save your work.
16.  Open the tc_cart.html file in your browser and verify that the page now shows the shopping cart data for the sample customer order.
```