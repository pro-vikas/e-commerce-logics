## Address

⬆️ [Go to main menu](README.md#e-commerce-logics) ⬅️ [Previous (Log and debug)](register.md) ➡️ [Next (Other)](register.md)

### Custom
- [User Address](#user-address)
- [Billing Address](#billing-address)
- [Shipping Address](#shipping-address)

### User Address

Where user currenty stays

``` 
    Required:
        a. Name ( also First name and Last name )
        b. Address Line 1 ( Flat number ) 
        c. Address Line 2 ( Street name )
        d. Near by 
        e. Country
        f. State
        g. City
        h. Locality or area
        i. pincode 

    Backend ( Additional )
        1. Is billing address  ( is_billing_address )
        1. Is shipping address  ( is_shipping_address )
        1. Address verified  ( is_address_verified )

    Validations:

        a. Name ( also First name and Last name ):
            1. Alphabhets only ( Valid name ) 
            2. Check already address submitted by user or not if yes then update
        
        Comming soon... 
  
```
