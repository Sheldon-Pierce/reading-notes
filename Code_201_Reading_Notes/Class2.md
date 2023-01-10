[Home](../README.md)

### Why do we need semantics?

Semantics are relied on everywhere around us—we rely on previous experience to tell us what the function of an everyday object is; when we see something, we know what its function will be. So, for example, we expect a red traffic light to mean "stop," and a green traffic light to mean "go." Things can get tricky very quickly if the wrong semantics are applied. (Do any countries use red to mean "go"? We hope not.)

In a similar vein, we need to make sure we are using the correct elements, giving our content the correct meaning, function, or appearance. In this context, the \<h1> element is also a semantic element, which gives the text it wraps around the role (or meaning) of "a top level heading on your page."

There are 6 levels of heading in HTML

### Superscript and subscript

You will occasionally need to use superscript and subscript when marking up items like dates, chemical formulae, and mathematical equations so they have the correct meaning. The \<sup> and \<sub> elements handle this job.

### Abbreviations

Another fairly common element you'll meet when looking around the Web is \<abbr> — this is used to wrap around an abbreviation or acronym. When including either, provide a full expansion of the term in plain text on first use, along with the \<abbr> to mark up the abbreviation. This provides a hint to user agents on how to announce/display the content while informing all users what the abbreviation means.

If providing the expansion in addition to the abbreviation makes little sense, and the abbreviation or acronym is a fairly shortened term, provide the full expansion of the term as the value of title attribute

### CSS

You can apply CSS with external, internal, or inline!

Problems with inline: It is the opposite of a best practice. First, it is the least efficient implementation of CSS for maintenance. One styling change might require multiple edits within a single web page. Second, inline CSS also mixes (CSS) presentational code with HTML and content, making everything more difficult to read and understand. Separating code and content makes maintenance easier for all who work on the website.

h2 is a selcetor, color and padding represent the properties, while black and 5px are teh declarations.

### JavaScript

A string is sequence of text enclosed in single quote marks.

Operators include addition, subtraction, multiplication, and division

You only have 5 tickets and you need to stop handing them out after the 5th customer, you can use a function to cut off at 5.

### If and Else Statements

An if statement checks a condition and if it evaluates to true then the code block will execute

There is a way to chain on extra choices/outcomes to your if...else — using else if. Each extra choice requires an additional block to put in between if () { } and else { }

#### Comparison Operators

- === and !== — test if one value is identical to, or not identical to, another.
- < and > — test if one value is less than or greater than another.
- <= and >= — test if one value is less than or equal to, or greater than or equal to, another.

#### Logical Operators

- && — AND; allows you to chain together two or more expressions so that all of them have to individually evaluate to true for the whole expression to return true.
- || — OR; allows you to chain together two or more expressions so that one or more of them have to individually evaluate to true for the whole expression to return true.

### Things I want to know more about