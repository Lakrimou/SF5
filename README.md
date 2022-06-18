# Custom Symfony Authenticator

## CheckPassportEvent

Dispatched after authenticator created the security passport. Listeners of this event do the actual authentication checks(like checking the passport, validating the CSRF token, check for if user is active etc)

overriding the authentication process to check informations to add some logic before authentication

![alt text](https://github.com/Lakrimou/SF5/blob/main/image.png?raw=true)