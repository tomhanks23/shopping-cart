Mom&Kids shopping carts' User Story:

1. I am a customer, I want to register in this system.
   * create user table
   * create registration html forms
   * client side js validation
   * php page to save user infomation to datebase 
   
2. I am a customer, I want to log in this system.
   * create log in form 
   * client side js validation
   * php validation

3. I am a customer, I want to see the items of this shopping website.
   * create product table
   * get products from db and show them to the client side

4. I am a customer, I want to buy things from this shopping website.
   * php : click an item and the page will jump to the item detail page from home page
   * when click "checkout" button, this order will jump into checkout page
   * create order table 
   * create line_item table
   * save item into line_item
   * save create a new order in order table and make the order status "ordered"

5. I am a customer, I want to pay for the goods which I bought.
   * update order table by change the order status into "paid"

6. I am the manager, I want to see how many deals recently happened.
   * create a new page to display data
   * select * from order table

7. I am the manager, I want to see how many users have registered to my website.
   * create a new page to display data
   * select * from user

8. I am the manager, I want to add, delete, update items.
   * create a new page to display data
   * add update form
   * insert into product table
   * update product table
   * delete record from product table
