## Login

⬆️ [Go to main menu](README.md#e-commerce-logics) ⬅️ [Previous (Log and debug)](register.md) ➡️ [Next (Other)](register.md)

### Custom
- [Login via email and password](#login-via-email-and-password)
- [Login via mobile and password](#login-via-mobile-and-password)
- [Login via username, email, mobile and password](#login-via-username-email-mobile-and-password)
- [Login via username and password](#login-via-username-and-password)
- [Login via mobile and otp](#login-via-mobile-and-otp)
- [Guest Login](#guest-login)

### Social Media
- [Login via Google](#login-via-google)
- [Login via Facebook](#login-via-facebook)
- [Login via Twitter](#login-via-twitter)
### Login via email and password

Basic login type `login with email and password`

```
    - Validations
    ### Web
            Email:
                1. Email is valid or not
                2. Email is register or not 
                3. Email is verify or not
                4. Check email status ( user is active, deactive, banned or suspended)

            Password:
                1. Password is 8 digits or else
                2. Password is matching

    ### API
            Check API Key is valid or not.

            Email:
                1. Email is valid or not
                2. Email is register or not 
                3. Email is verify or not
                4. Check email status ( user is active, deactive, banned or suspended)

            Password:
                1. Password is 8 digits or else
                2. Password is matching
```

### Comming Soon
