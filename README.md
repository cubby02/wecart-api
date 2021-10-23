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

## register
/register.php?buyer&name={FULL_NAME_HERE}&username={USERNAME}&password={PASSWORD}&brgy={BARANGAY}&sitio={SITIO}&street={STREET}&contact_num={CONTACT_NUMBER}&contact_email={CONTACT_EMAIL}
