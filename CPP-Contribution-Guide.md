Language: C++

For code format we mostly use the https://docs.microsoft.com/en-us/dotnet/fundamentals/code-analysis/code-style-rule-options?view=vs-2022
With a few tweeks for prefrence. You can use the .clangformat file to help you with this.

When writing functions we write them in cammel case:

"**thisIsAFunctionName()**" ✅

"**ThisIsAFunctionName()**" ❌

"**thisisafunctionname()**" ❌

"**this_is_a_function_name()**" ❌

Variable names are always lower case with underscores to split words:

"**int var_x = 0;**" ✅

"**int Var = 0;**" ❌

"**int Varx = 0;**" ❌

Enum names are the same as functions but enum values are all uppercase and words split by underscore:

enum **exampleEnum**
{

"**ENUM_VALUE**" ✅

"**enum_value**" ❌

}

C style casting is discouraged please try to use **static_cast<?>(?);**
