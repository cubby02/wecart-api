# wecart-api

**description:** A comprehensive documentation of wecart-api.

### Format

wecart API is represented in JSON format, example:
```
[
    {
        "acc_type": "seller",
        "store_name": "apple",
        "description": null,
        "full_name": "Dan",
        "username": "Danjej3m0n",
        "password": "0a113ef6b61820daa5611c870ed8d5ee",
        "brgy": "Bauan",
        "sitio": "Villa Chuchu",
        "street": "Bulag Street",
        "contact_num": "09123456789",
        "contact_email": " redacted@gmail.com"
    },
```

## register user
```
wecart-api/register.php?buyer&name=[FULL_NAME_HERE]&username=[USERNAME]&password=[PASSWORD]&brgy=[BARANGAY]&sitio=[SITIO]&street=[STREET]&contact_num=[CONTACT_NUMBER]&contact_email=[CONTACT_EMAIL]
```

## register seller
```
/wecart-api/register.php?seller&store_name={STORE_NAME}&description={STORE_DESCRPITION}&password=[PASSWORD]&brgy=[BARANGAY]&sitio=[SITIO]&street=[STREET]&contact_num=[CONTACT_NUMBER]&contact_email=[CONTACT_EMAIL]
```
## Login
```
/wecart-api/login.php?username=[USERNAME]&password=[PASSWORD]
```
## Change Password
```
/wecart-api/changepass.php?username=[USERNAME]&oldpass=[CONFIRM_OLD_PASSWORD]&newpass=[NEW_PASSWORD]
```

```
## show user profile-info
```
/wecart-api/profile_info.php?username=[USERNAME]

```
