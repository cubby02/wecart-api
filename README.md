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
    },
```

We use a termporary API Server at the moment. Paki copy paste nalang ng maigi thankyou.

Our API server may vary from: *.ngrok.io

## register user
```
https://*.ngrok.io/wecart-api/register.php?buyer&name=[FULL_NAME_HERE]&username=[USERNAME]&password=[PASSWORD]&brgy=[BARANGAY]&sitio=[SITIO]&street=[STREET]&contact_num=[CONTACT_NUMBER]&contact_email=[CONTACT_EMAIL]
```

## register seller
```
https://*.ngrok.io/wecart-api/register.php?seller&store_name=[STORE_NAME}&description=[STORE_DESCRPITION]&name=[FULL_NAME_HERE]&username=[USERNAME]&password=[PASSWORD]&brgy=[BARANGAY]&sitio=[SITIO]&street=[STREET]&contact_num=[CONTACT_NUMBER]&contact_email=[CONTACT_EMAIL]
```
## Login
```
https://*.ngrok.io/wecart-api/login.php?username=[USERNAME]&password=[PASSWORD]
```
## change password
```
https://*.ngrok.io/wecart-api/changepass.php?username=[USERNAME]&oldpass=[CONFIRM_OLD_PASSWORD]&newpass=[NEW_PASSWORD]

```
## show user profile-info
```
https://*.ngrok.io/wecart-api/profile_info.php?username=[USERNAME]

```
## show all registered users/sellers
```
https://*.ngrok.io/wecart-api/showusers.php
```
## show all available stores
```
https://*.ngrok.io/wecart-api/showusers.php?storelist
```
