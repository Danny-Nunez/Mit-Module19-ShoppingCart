# Mit-Module19-ShoppingCart

In Module 19: Shopping Cart Exercise, We learned how to integrate a React front end with the back end and we also learned how to use tools like Strapi, Postman, Express, and node. You’ll use Strapi to create a Database, then use Express and Postman to set up and test the communication between Strapi and the front end. We also utilized picsum api to random generate new image on load.

<img width="1407" alt="Screen Shot 2023-04-04 at 6 25 22 PM" src="https://user-images.githubusercontent.com/114783191/229937016-0cfec3b1-1d74-43b5-9a53-8c4a3dafe606.png">

# How to run

To run this React shopping cart. You must have strapi running and enter products and update the api address to your localhost1337 address. This will allow you to communicate with your list of items. Open the index.html on your live server and make sure strapi is running. To test the api calls please use postman.

# Api Calls used 

Get https://localhost:1337/api/products

Post https://localhost:1337/api/products
<br>
Json Body Example of entering item
{
    "data": 
        {
                "name": "Mangos",
                "country": "Italy",
                "cost": 3,
                "instock": 10
        }
}

# Tech used 

1. React<br>
2. Strapi<br>
3. Postman<br>
4. Boostrap
