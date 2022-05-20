# Class 10 Notes

### **Error Handling & Debugging**

**Execution Content**
Every statement in a script lives in one of three execution contexts:

- **Global Context**
<br>
Code that is in the script, but not in a function. There is only on global context inany age

- **Function Context**
<br>
Code that is beingrun within a function. Each function has its own function context.

- **Eval Context (Not Known)**
<br>
Text is executed like code in an internal function called eval ()

## **Variable Scope**
The first two execution contexts correspond with the notion of scope

- **Global Scope**
<br>
If a variable is declared outside a function, it can be used anywhere because it has a global scope. If you do not use the **var** keyword when creating a variable, it is placed in global scope.

- **Function-Level Scope**
<br>
When a variable is declared within a function, it can only be used within that function. This is because it has function-level scope.

## Types of Errors

- Syntax Error- Syntax is not correct
- Reference Error- Variable does not exist
- Eval Error- Incorrect use of eval() Function
- URI Error- Incorrect use of URI Functions
- Type Error- Value is unexpected data type
- Range Error- Number outside of range
- Error- Generic error objet
- Nan- Not an error

## Debugging Tips

- Try another browser
- Add numbers
- Strip it back
- Explaining the code
- Search
- Code playgrounds
- Validation tools
- Go back to basics
- Data type issues
