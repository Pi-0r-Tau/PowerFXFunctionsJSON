# PowerFXFunctionsJSON
Power Fx functions in a standardized JSON format

### Method
Microsoft:
src/libraries/Microsoft.PowerFx.Core/Texl/Builtins

Reviewed C# Function files and converted manually to JSON. 

### JSON Structure
- functions: Container for function definitions.
- name: Identifies the function.
- description: Explains the function's purpose.
- syntax: How to call the function.
- parameters: Inputs required by the function.
- name: Name of parameter.
- type: Data type of parameter.
- description: Explanation of the parameter's purpose.
- constraints: Specifies constraints for parameters.
- parameter constraints: Ensures parameters meet certain criteria.
- validators: Validates the parameters' types.
- parameter validators: Ensures parameters are of the correct type.
- signatures: Valid combinations of parameters for calling the function.
- valid parameter combinations: Specifies valid parameter sets.
- errorHandling: Defines how to handle errors.
- errors: Possible errors that can occur.
- error code: Unique identifier for the error.
- error message: Explanation of the error.

### Use cases
Up to you.

#### TODO:
- Review Validators value reference and types
