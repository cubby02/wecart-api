# wecart-api

**description:** A comprehensive documentation of wecart-api.

### Format

wecart API is represented in JSON format, example:
```
[
    {
        "acc_type": "seller",
        "store_name": "Apple",
        "description": "Gadget Store",
        "full_name": "Dan",
        "username": "Danjej3m0n",
        "password": "0a113ef6b61820daa5611c870ed8d5ee",
        "brgy": "Bauan",
        "sitio": "Villa Chuchu",
        "street": "Bulag Street",
        "contact_num": "09123456789",
        "contact_email": "redacted@gmail.com"
    }
]
```

~~We use a termporary API Server at the moment.~~ Paki copy paste nalang ng maigi thankyou.

Live API is now available at: https://wecart.gq/

## register user
```
https://wecart.gq/wecart-api/register.php?buyer&name=[FULL_NAME_HERE]&username=[USERNAME]&password=[PASSWORD]&brgy=[BARANGAY]&sitio=[SITIO]&street=[STREET]&contact_num=[CONTACT_NUMBER]&contact_email=[CONTACT_EMAIL]
```
## register agent
```
https://wecart.gq/wecart-api/register.php?agent&name=[AGENT_NAME]&username=[AGENT_USERNAME]&password=[AGENT_PASSWORD]&brgy=[BARANGAY]&sitio=[SITIO]&street=[STREET]&contact_num=[AGENT_CONTACT_NUMBER]&contact_email=[AGENT_CONTACT_EMAIL]
```
## register seller
```
https://wecart.gq/wecart-api/register.php?seller&store_name=[STORE_NAME]&store_type=[TYPE_OF_STORE]&description=[STORE_DESCRPITION]&name=[FULL_NAME_HERE]&username=[USERNAME]&password=[PASSWORD]&brgy=[BARANGAY]&sitio=[SITIO]&street=[STREET]&contact_num=[CONTACT_NUMBER]&contact_email=[CONTACT_EMAIL]
```
## Login
```
https://wecart.gq/wecart-api/login.php?username=[USERNAME]&password=[PASSWORD]
```
## Logout
```
https://wecart.gq/wecart-api/logout.php?username=[USERNAME]
```
## change password
```
https://wecart.gq/wecart-api/changepass.php?username=[USERNAME]&oldpass=[CONFIRM_OLD_PASSWORD]&newpass=[NEW_PASSWORD]

```
## show user profile-info
```
https://wecart.gq/wecart-api/profile_info.php?username=[USERNAME]

```
# upload user profile photo
```
POST: username,image => https://wecart.gq/wecart-api/upload_user_profile.php
```
## show all registered users/sellers
```
https://wecart.gq/wecart-api/showusers.php
```
## show all available stores
```
https://wecart.gq/wecart-api/showusers.php?storelist
```
## show all agents
```
https://wecart.gq/wecart-api/showusers.php?agents
```
# show online users
```
https://wecart.gq/wecart-api/showusers.php?isactive
```
# show online agents
```
https://wecart.gq/wecart-api/showusers.php?agents=isactive
```
# Seller: add product
```
https://wecart.gq/wecart-api/add_product.php?username=[USERNAME]&product_name=[PRODUCT_NAME]&product_type=[PRODUCT_TYPE]&description=[DESCRIPTION]&stock=[STOCK]&price=[PRICE]
```
# Seller: add product (product image)
```
https://wecart.gq/wecart-api/product_image_upload.php
```
# show all products
```
https://wecart.gq/wecart-api/showproducts.php
```
# show all products from specific seller
```
https://wecart.gq/wecart-api/showproducts.php?seller=[SELLER_USERNAME]
```
# show a product type from specific seller 
```
https://wecart.gq/wecart-api/showproducts.php?seller=[SELLER_USERNAME]&product_type=[product_type]
```
