## Getting Started

- Install the version of Node JS for your OS https://nodejs.org/en/download
- From a terminal run the following commands to check if the installation was successful:
  - `$ node -v`
  - `$ npm -v`
  - Set PATH environment variable to path/to/bin/node and path/to/bin/npm if the above commands failed to return the version number.
- In the terminal install dependencies using the command:
    `$ npm install`
- In the terminal run the local server using the command:
  - `node form-server.js`
- Open "form.html" in a browser. Enter username and password and click "Submit".

## Questions for you to answer
1. What is the purpose of the _action_ attribute in the _form_ tag?<br>
Ans: On click of submit button, the form control will be tranferred to the server running on the path - http://localhost:3000/login

2. What is the purpose of the _method_ attribute in the _form_ tag?<br>
Ans: It specifies the type of HTTP request that we are trying to call on form submission.

3. What is the purpose of the _name_ attribute in the _input_ tag?<br>
Ans: The _name_ attribute works as an identifier for the input tag which is used for inputting name in the form.

4. What is the purpose of the _type_ attrbute in the _input_ tag?<br>
Ans: It specifies the type of the input. It can be a checkbox, a textbox, a password input, or a button.

5. What is the purpose of the _label_ tag?<br>
Ans: _label_ tag assigns a label for an input tag.

6. What is the purpose of the _required_ attribute?<br>
Ans: The _required_ attributes makes the input field as a mandatory field.
