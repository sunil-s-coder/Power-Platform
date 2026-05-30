# PowerFx

## 1. Collection & Table Functions

| Function          | Short Definition |
|-------------------|------------------|
| Table()           | Creates an in-memory table from explicitly provided records |
| Collect()         | Adds one or more records to a collection |
| Clear()           | Removes all records from a collection |
| ClearCollect()    | Clears a collection and loads new records |
| Patch()           | Updates specific fields in one or more records |
| Update()          | Replaces an entire record in a collection |
| UpdateIf()        | Updates records that meet a condition |
| Remove()          | Deletes a specific record from a collection |
| RemoveIf()        | Deletes records matching a condition |
| AddColumns()      | Adds calculated columns to a table |
| DropColumns()     | Removes specified columns from a table |
| RenameColumns()   | Renames one or more columns |
| ShowColumns()     | Returns only selected columns from a table |
| First()           | Returns the first record of a table |
| FirstN()          | Returns the first N records |
| Last()            | Returns the last record of a table |
| LastN()           | Returns the last N records |
| Index()           | Finds a record in a collection basis a index/row number |
| CountRows()       | Returns the total number of records |
| Filter()          | Returns records that match a condition |
| Sort()            | Sorts records by a single column |
| SortByColumns()   | Sorts records using column names as text |
| LookUp()          | Finds a single record matching a condition |
| Concat()          | Concatenates text from a column across all records into a single string |
| Sequence()        | Generates a single-column table of sequential numbers |
| Distinct()        | Extract a unique list of values from a single column of a table or collection |
| Search()          | Finds the position of a substring within text or columns |
| SaveData()        | Saves a collection locally on the device for offline use. |
| LoadData()        | Loads previously saved local data into a collection. |
| Shuffle()         | Randomly rearranges the order of records in a table. |
| Relate()          | Creates a relationship between records in related Dataverse tables. |

---

## 2. Aggregate, Behavior & Scalar Functions

| Function       | Category   | Short Definition |
|----------------|------------|------------------|
| Max()          | Aggregate  | Returns the highest value from a table or list |
| Min()          | Aggregate  | Returns the lowest value from a table or list |
| Sum()          | Aggregate  | Returns the total of numeric values |
| Average()      | Aggregate  | Returns the mean of numeric values |
| Round()        | Scalar     | Rounds a number to a specified number of decimal places |
| RoundDown()    | Scalar     | Rounds a number down to the specified decimal places |
| RoundUp()      | Scalar     | Rounds a number up to the specified decimal places |
| Abs()          | Scalar     | Returns the absolute (non-negative) value |
| Sqrt()         | Scalar     | Returns the square root of a number |
| Power()        | Scalar     | Raises a number to a specified power |
| Log()          | Scalar     | Returns the natural logarithm of a number |
| Exp()          | Scalar     | Returns *e* raised to the power of a number |
| Trunc()        | Scalar     | Removes the decimal portion of a number |
| Mod()          | Scalar     | Returns the remainder after division |
| Value()        | Scalar     | Converts text to a numeric value |
| Rand()         | Scalar     | Returns a random decimal number between 0 and 1 |
| RandBetween()  | Scalar     | Returns a random whole number between two specified values |

---

## 3. Conditional Logic & Decision Functions

| Function        | Short Definition |
|-----------------|------------------|
| If()            | Executes expressions based on one or more conditions |
| Switch()        | Evaluates a value against multiple conditions |
| ForAll()        | Executes a formula for each record in a table |
| Coalesce()      | Returns the first non-blank value |
| IsBlank()       | Checks whether a value is blank |
| IsEmpty()       | Checks whether a table contains no records |
| IsNumeric()     | Determines whether a value is numeric |
| StartsWith()    | Checks if text starts with a value |
| EndsWith()      | Checks if text ends with a value |
| IsMatch()       | Checks if text matches a pattern using a regular expression |
| IsBlankOrError()| Returns true if a value is blank or contains an error |
| IsToday()       | Checks if a date value is today |
| Not()           | Negates the boolean value |

---

## 4. Variables & Execution Control Functions

| Function         | Short Definition |
|------------------|------------------|
| Set()            | Creates or updates a global variable |
| UpdateContext()  | Creates or updates a screen-level variable |
| With()           | Defines temporary variables within a formula |
| Concurrent()     | Executes multiple formulas in parallel |

---

## 5. User & Environment Functions

| Function | Short Definition |
|----------|------------------|
| User()   | Returns details of the current logged-in user |
| Param()  | Retrieves a parameter value passed in the app URL |

---

## 6. Text Manipulation

| Function        | Short Definition |
|-----------------|------------------|
| Text()          | Converts and formats values as text |
| Concatenate()   | Joins multiple text values into a single text string |
| Upper()         | Converts text to uppercase |
| Lower()         | Converts text to lowercase |
| Left()          | Returns characters from the start of a text value |
| Right()         | Returns characters from the end of a text value |
| Mid()           | Returns a substring from a specified position |
| Len()           | Returns the number of characters in a text value |
| Substitute()    | Replaces all occurrences of a substring with new text |
| Replace()       | Replaces characters in a text string at a specified position |
| Trim()          | Removes leading and trailing spaces from text |
| TextPosition()  | Returns the position of a substring in a text value |
| MatchAll()      | Returns all matches of a regular expression in a text string |

---

## 7. Date & Time Functions

| Function        | Short Definition |
|-----------------|------------------|
| Now()           | Returns the current date and time |
| Today()         | Returns the current date |
| DateAdd()       | Adds a specified time unit to a date |
| DateDiff()      | Returns the difference between two dates |
| Month()         | Returns the month from a date |
| Year()          | Returns the year from a date |
| Hour()          | Returns the hour from a date/time value |
| Weekday()       | Returns the day of the week from a date |
| DateValue()     | Converts text to a date |
| TimeValue()     | Converts text to a time |
| DateTimeValue() | Converts text to a date and time |

---

## 8. Form & Control-Specific Functions

| Function        | Scope         | Short Definition |
|-----------------|---------------|------------------|
| SubmitForm()    | Form-only     | Submits changes from a form to the data source |
| ResetForm()     | Form-only     | Resets a form to its initial state |
| NewForm()       | Form-only     | Switches a form to new record mode |
| EditForm()      | Form-only     | Switches a form to edit existing record mode |
| ViewForm()      | Form-only     | Switches a form to read-only mode |
| Validate()      | Form-only     | Validates form input based on data source rules |
| FormMode()      | Form-only     | Returns the current mode of a form |
| Defaults()      | Data source   | Returns the default record for a data source |
| DataSourceInfo()| Data source   | Returns metadata about a data source |
| Refresh()       | Data source   | Refreshes data from the connected data source |
| Reset()         | Control-only  | Resets a control to its default value |
| Select()        | Control-only  | Programmatically triggers the OnSelect action of a control |

---

## 9. Navigation & UX Behavior

| Function   | Short Definition |
|------------|------------------|
| Navigate() | Navigates to another screen |
| Back()     | Returns to the previous screen |
| Exit()     | Closes the app |
| Launch()   | Opens a URL or external application |
| Notify()  | Displays a notification message |

---

## 10. Data Shaping & Type Handling

| Function   | Short Definition |
|------------|------------------|
| IsType()   | Checks whether a record is of a specified table type |
| AsType()   | Casts a polymorphic record to a specific table type |
| GroupBy()  | Groups records by one or more columns |
| Ungroup()  | Expands grouped records back into a flat table |

---

## 11. Type Conversion & Formatting Functions (Power Fx)

| Function       | Short Definition |
|----------------|------------------|
| Boolean()      | Converts a value to true or false |
| GUID()         | Converts text to a GUID value |
| JSON()         | Converts a value to JSON text |
| ParseJSON()    | Converts JSON text to objects |
| Char()         | Converts a number to its corresponding character |
| Code()         | Converts a character to its ASCII number |
| Language()     | Returns the language tag for the current locale |

---

## 12. Color Functions

| Function      | Short Definition |
|---------------|------------------|
| RGBA()        | Creates a color from Red, Green, Blue, and Alpha (transparency) values |
| RGB()         | Creates a color from Red, Green, and Blue values (fully opaque) |
| ColorValue()  | Converts a text string to a color value |
| ColorFade()   | Returns a lighter or darker version of a color |

---

## 13. Error Handling Functions

| Function / Property | Short Definition |
|--------------------|------------------|
| IsBlank()          | Returns true if a value is blank |
| IsError()          | Returns true if a value or formula results in an error |
| IfError()          | Executes a formula and provides a fallback value if it fails |
| IsBlankOrError()   | Returns true if a value is blank or results in an error |
| Trace()            | Logs diagnostic information for monitoring and debugging |
| Error()            | Creates and raises a custom error in the app |
| FirstError         | Returns information about the first error captured at the app level |
| AllErrors          | Returns a table of all errors captured at the app level |
| App.OnError        | App-level property that runs when a runtime error occurs |

---

## 13. Data Source Functions

| Function / Property | Short Definition |
|--------------------|------------------|
| Refresh()         | Refreshes a data source by retrieving the latest data from the server. |
| Copy()            | Copies data from variable to Clipboard |
| Download()        | Downloads file from given input URL |
| Print()           | Prints the current screen or generates a printable version of the app content. |
| Confirm()         | Displays a confirmation dialog and returns true if the user confirms, otherwise false. |

---

### 2. Live Monitoring
- Use **App.OnError** to monitor and handle errors during app execution.
- Provides global error handling without interrupting app flow.




