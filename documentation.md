# Basic Calculator Implementation Documentation

## add Function
- **Purpose**: Adds two numbers.
- **Parameters**:
  - `double a`: The first number.
  - `double b`: The second number.
- **Returns**: The sum of `a` and `b`.

## subtract Function
- **Purpose**: Subtracts one number from another.
- **Parameters**:
  - `double a`: The number to be subtracted from.
  - `double b`: The number to subtract.
- **Returns**: The result of `a - b`.

## multiply Function
- **Purpose**: Multiplies two numbers.
- **Parameters**:
  - `double a`: The first number.
  - `double b`: The second number.
- **Returns**: The product of `a` and `b`.

## divide Function
- **Purpose**: Divides one number by another.
- **Parameters**:
  - `double a`: The dividend.
  - `double b`: The divisor.
- **Returns**: The quotient of `a / b`.
- **Error Handling**: Prints an error message and exits if `b` is zero.

## main Function
- **Purpose**: The entry point of the calculator program. It reads input from the user, performs the requested operation, and prints the result.
- **Workflow**:
  1. Reads the first number from the user.
  2. Reads the operator from the user.
  3. Reads the second number from the user.
  4. Uses a switch-case statement to call the appropriate arithmetic function based on the operator.
  5. Prints the result of the operation.
  6. Handles invalid operators by printing an error message.
