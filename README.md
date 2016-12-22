# ng-contact-formspree
***
A simple form using Angular for validation and formspree.io for email notifications. The user fills out their full name, email, and a message.
If validated, the user is directed to a thank you page.
***
## Installation
> npm install

> bower install

## Serve the files
> gulp serve

## Example Form
> Found at app/index.html

***
## Configuring formspree
In the form tag, the action attribute needs to have the client's email
```
action="https://formspree.io/YOUR-EMAIL@gmail.com"
```
*After submitting the form for the first time, the client needs to confirm their email before they are able to use the service. After confirming, the form will work and the client can receive emails.
**Don't forget to repeat this process on production.**
**Otherwise, it will not work until the client gives formspree.io permission to use their email**
***
