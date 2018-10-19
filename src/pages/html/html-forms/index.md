---
title: HTML Forms
---
## HTML Forms

Forms are used to collect data entered by a user, which are then sent to the server for further processing. They can be used for different kinds of user inputs, such as name, email and others.

Form contains control elements which are wrapped around ```<form></form>``` tags, like ```input```, which type can be:

- ```text```
- ```email```
- ```password```
- ```checkbox```
- ```radio```
- ```submit```

Code example:
```html
<form>
    <label for="username">Username:</label>
    <input type="text" name="username" id="username">
    <label for="password">Password:</label>
    <input type="password" name="password" id="password">
    <input type="radio" name="gender" value="male">Male<br>
    <input type="radio" name="gender" value="female">Female<br>
    <input type="radio" name="gender" value="other">Other
    <input type="submit" value="Submit">
</form>
```

Other elements that form can contain:

- ```textarea``` - is a multiline box which is most often used for adding some text eg. comment. Size of textarea is defined by number of rows and columns.
- ```select``` - together with ```<option></option>``` tag creates drop-down select menu.


## More Information

HTML Forms are required when you want to collect data from your site's visitors. For example, during user registration you would like to collect information such as name, email address, credit card, etc.

A form will take input from the site visitor and then will post it to a back-end application such as CGI, ASP Script or PHP script. A back-end application will perform required processing on the passed data based on defined business logic inside the application.

There are various form elements available like text fields, textarea fields, drop-down menus, radio buttons, checkboxes to style the forms how you want.
