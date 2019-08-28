# Challenge

1. Objective:
Write a basic shopping cart in React and Redux.

    1.1. Supplied: Products in an array (these do not require any editing).
    
    ```js
    const products = [{
        name: “Sledgehammer”,
        price: 125.75
    }, {
        name: “Axe”,
        price: 190.50
    }, {
        name: “Bandsaw”,
        price: 562.13
    }, {
        name: “Chisel”,
        price: 12.9
    }, {
        name: “Hacksaw”,
        price: 18.45
    }]
    ```

   1.2.  Requirements: 
    * The cart will need to keep its state during page loads / refreshes.
    * List Products – these should be listed at all times to allow adding of products
    * Products should be listed in this format: product name, price, link to add product to the cart.
    * Must be able to add a product to the cart.
    * Must be able to view current products in the cart.
    * The cart should list the products in this format: product name, price, quantity, total, a remove link.
    * Product totals should be tallied to give an overall total
    * The user can remove a product from the cart
    * Adding an existing product will only update existing cart product quantity (e.g. adding the same product twice will NOT create two cart items)
    * All prices should be displayed with 2 decimal places.
    * Error checking will be set to strict for viewing completed code.
    * Project will work as expected with the latest version of React.
    * Use best practices.
