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
1. What is the purpose of the _action_ attribute in the _form_ tag?
   To connect the html block to the API endpoint. Submit button hits the API with the provided
   information.
2. What is the purpose of the _method_ attribute in the _form_ tag?
   To ensure the type of the API is correct.
3. What is the purpose of the _name_ attribute in the _input_ tag?
   To set the variable for the input for the endpoint. The information passed will be stored the
   corresponding variable name.
4. What is the purpose of the _type_ attribute in the _input_ tag?
   The type of the input declaration which will tell the browser what information is being passed.
5. What is the purpose of the _label_ tag?
   Shows the label on the UI. Shows the user what information needs to be provided.
6. What is the purpose of the _required_ attribute?
   Will throw an error if the input is empty.
