1. This server will run on port 3000

2. There are two apis created for this server- 
    1.  /getAvailableItems  e.g..   localhost:3000/getAvailableItems => to get all the available items
    2.  /placeOrder     e.g..localhost:3000/placeOrder  ==> to place the order

3. github link  - https://github.com/abhiJit1993/vedantu



//  Things that I have'nt implemented
1.   check for login  and getting the userId
2. For Race conditions I will add a 'Node-scheduler' and check the cart_items field in accounts collection after each hour to validate.

-----------Table Structure----------

3 COLLECTIONS - accounts, inventories, order_history




