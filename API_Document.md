 //PAGE 1

# list of category
https://bikeswale.herokuapp.com/categories



//PAGE 2

# all bikes
https://bikeswale.herokuapp.com/bikes

# bikes wrt category
https://bikeswale.herokuapp.com/catbike?categoryId=4

# bikes wrt to brand id <Done>
https://bikeswale.herokuapp.com/bikes?brand=7

# bikes wrt brand id  lprice hprice <Done>
https://bikeswale.herokuapp.com/filter/2?lprice=20000&hprice=80000

# category wrt brand Name
https://bikeswale.herokuapp.com/filter/2?category=Scooter


<!-- example - brand id 8 means keeway and category=Sport Bikes -->
https://bikeswale.herokuapp.com/filter/8?category=Sport%20Bikes

# bikes with brandId wrt category price
<!-- brand id 8  sports bike 1100000 to 32490000  -->
https://bikeswale.herokuapp.com/filter/11?category=Sport%20Bikes&lprice=1100000&hprice=32490000

# bikes wrt category and brand id
https://bikeswale.herokuapp.com/filtercat/1?brandId=7


# bikes also (wrt category) and lprice and hprice
https://bikeswale.herokuapp.com/filtercat/1?lprice=100000&hprice=200000


# bikes also (wrt category) and brandid and lprice and hprice with sort
https://bikeswale.herokuapp.com/filtercat/4?brandId=7&lprice=100000&hprice=200000&sort=-1



// PAGE 3

# Details of bike
https://bikeswale.herokuapp.com/details/4.8

# More bikes of same brand in details page
https://bikeswale.herokuapp.com/more/1



// PAGE 4
# Menu Details (post)
https://bikeswale.herokuapp.com/menuitems
    {
        "id": [2.1,3.4,4.10]
    }
# Place Order (post)
https://bikeswale.herokuapp.com/placeOrder
    {
    "order_id": 4,
    "name": "tuntun",
    "number": "124567870",
    "email": "mahi@gmail.com",
    "item":[3,4,66]
    }


// PAGE 5

# List of Order
https://bikeswale.herokuapp.com/orders

# List of Order wrt to email
https://bikeswale.herokuapp.com/orders?email=mahi@gmail.com

# Update Order
https://bikeswale.herokuapp.com/updateOrder/5
{
    "Bank_name":"PNB",
    "date":"2/11/22",
    "status":"Pending"
}
<!--{
        "_id": "66",
        "orderId": 5,
        "name": "SITARA",
        "number": "1245678730",
        "email": "ma3hi@gmail.com",
        "item": [
            3,
            4,
            636
        ],
        "bank": "Pending",
        "status": "Pending"
    }-->

# Delete Order (Delete)
https://bikeswale.herokuapp.com/deleteOrder/634dc36bf1b24a81336332d9
