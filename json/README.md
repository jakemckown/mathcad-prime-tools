# JSON support for PTC Mathcad Prime

Inspired by, and in some parts ported directly from VBA to Mathcad from, [Tim Hall](https://github.com/timhall)'s [VBA-JSON](https://github.com/VBA-tools/VBA-JSON).

## Examples

Read and parse JSON file:

![Read and parse JSON file](Read_and_Parse_JSON.png)

Update JSON object:

![Update JSON object](Update_JSON.png)

## Installation

Install functions in the following order:
1. *Unicode*
2. *Concatenate*
3. *ParseError<sub>JSON</sub>*
4. *SkipSpaces<sub>JSON</sub>*
5. *ParseString<sub>JSON</sub>*
6. *ParseKey<sub>JSON</sub>*
7. *ParseNumber<sub>JSON</sub>*
8. *ParseLiteral<sub>JSON</sub>*
9. *ParsePrimitive<sub>JSON</sub>*
10. *ParseValue<sub>JSON</sub>*
11. *Parse<sub>JSON</sub>*
12. *GetValue<sub>JSON</sub>*
13. *SetValue<sub>JSON</sub>*

Mathcad has its own programming language, but it's embedded in the Worksheet and not directly available as text. There are three methods for installation. 

### Method 1: Copy from the MCDX file

1. Download the MCDX file.
2. Copy the functions from JSON.mcdx.
3. Paste the functions into your own Worksheet.

### Method 2: Include the MCDX file

1. Download the MCDX file.
2. In Mathcad, include a Worksheet with CTRL+SHIFT+W.
3. Click on the *Include* button.
4. Browse for the MCDX file.

### Method 3: Copy from the TXT files

For each TXT file:
1. Copy the text from the TXT file.
2. In Mathcad, insert a Math Region with CTRL+SHIFT+M.
3. Paste the text into the Math Region. The function will be rendered as math instead of text.
