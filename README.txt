NOTE: 
Not all error trapped in the inputs
Doesn't change the error message

Process:
- click on the register here to be directed to the registration form
- click the button to submit form 



3 sins I have attempted to solve:

Sin: Not querying or return the whole row but just the needed entries
- found at the RegistrationController return statement

Sin: Never hardcode all your queries
- using different controllers instead of placing all query statements in one file
- Controllers in the framework

Sin: not validating input
- validating datatype as early as in the input statements
- only insert email if FILTER_VALIDATE_EMAIL is not null AKA email is a valid one
- alerts the users that an email is wrong or taken
