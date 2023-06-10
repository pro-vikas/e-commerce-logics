## API

⬆️ [Go to main menu](README.md#laravel-tips) ⬅️ [Previous (Log and debug)](register.md) ➡️ [Next (Other)](register.md)

### Custom
- [Login via email and password](#api-resources-with-or-without-data)
- [Login via mobile and password](#conditional-relationship-counts-on-api-resources)
- [Login via username, email, mobile and password](#get-bearer-token-from-authorization-header)
- [Login via username and password](#avoid-n1-queries-in-api-resources)
- [Login via mobile and otp](#api-return-everything-went-ok)
- [Guest Login](#api-return-everything-went-ok)

### Social Media
- [Login via Google](#sorting-your-api-results)
- [Login via Facebook](#customize-exception-handler-for-api)
- [Login via Twitter](#force-json-response-for-api-requests)
- [API Versioning](#api-versioning)

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
