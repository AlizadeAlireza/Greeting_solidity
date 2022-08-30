1. we declare a contract 

2. we declare state variables

    - whenever define a state variable you automatically get for free 
    a getter function with the same name as variable.

3. make a constructor that initialize contract state variables

    - a contract can have only one constructor and executed once when a contract is created.
    - In case, no constructor is defined, a default constructor is present in the contract.

4. we get our new name via setName function

5. we return our greeting string via getGreeting function with combination of greetingPrefix state variable and our newName that we created in setName function with abi.encodePacked().

    - this func have view means that can't be changed
