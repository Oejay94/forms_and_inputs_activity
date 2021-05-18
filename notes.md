# Steps for the Activity

## 1. Make Form in HTML
   * Use formtags
 \
  ```<form></form>```
   * **both of the following tags are child elements of the form element.**
   * Use label tags to give a name for field. We will need one for Name and Email
 \
 ```<label></label>```
   * give each label tag a 'for field' that matches input tag
    \
    ```<label for='name_input'>Name</label>```
   * Use input tags to create fields the user will fill out for Name and Email
 \
 ```<input></input>```
   * Each input field needs some fields
      * an id field that matches the label's for field
      * a type field so we know what value will be used
      * a placeholder field for user to read and will be overwritten when the user types in their response.
      * a required field to let the site know if the field MUST be filled out in order for the form to be used.
   * in the end the tag will look something like this
   \
   ```<input id="name_input" type="text" placeholder="What's your name?" required />```
   * Then we make a label and textarea for the message
   * Lastly we will make a button and give it an id so we make this form do something!

## 2. Make that Button work!
   * make a variable and get the id of the button.

   * Use the addEventListener method so the button actually does something on click.

   * Inside the eventListener callback function, get the id of each input and the *value* of each input.
      * ```.value``` is a method used to get whatever the user typed into each field.

   * using the variables that gets the value from each field, create an alert message that uses each of the feilds. It can say whatever we want.

   * add ```event.preventDefault``` to stop the form from being submitted to the site. 
