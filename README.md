# my-first-csharp

## Notes

- WriteLine appends a newline after the output
- Inside the double-quotation marks in C#, is called literal string

### `Console.WriteLine("Hello");`

- `Console` : class
- `.` : a member access operator, navigate from the class to one of its methods
- `WriteLine()`: Method
  - `()`: method unnvocation operator
- `;`: end of statement operator

### Literal Values

- `char`: character, single quotation
  - double quotations creates a `string` data type
- `int`: integer
- floating point literals
  - float : ~6-9 digits, **F** (literal suffix) after number (not case sensitive)
  - double: ~15-17 digits, defaults to double if not specified
  - decimal: 28-29 digits, **m** (literal suffix) after number
- Boolean: true or false

### Variable names rules + convention

- alphanumeric characters and underscore
- must begin with \_ or alphabetical letter not number
- case sensitive
- must not be a C# keyword
- camel case
- shouldn't include the data type of the variable
  - so dont do `string strValue`

The var keyword tells the C# compiler that the data type is implied by the assigned value. Using var requires an assignment or there will be error.

```
var message = "Hello world!"; // so its implied that var is a string
message = 10.703m; // this would throw an error
```
