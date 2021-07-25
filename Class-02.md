# Read: 02 - HTML Text, CSS Introduction, and Basic JavaScript Instructions
## ***HTML & CSS***
**1. Text**
* how to add markup to the text that
appears on your pages. You will learn about:
    + Structural markup: the elements that you can use to
describe both headings and paragraphs
    + Semantic markup: which provides extra information; such
as where emphasis is placed in a sentence, that something
you have written is a quotation (and who said it), the
meaning of acronyms, and so on
* Two views of the page you are creating: a visual editor and a
code view.
* HTML elements are used to describe the structure of
the page (e.g. headings, subheadings, paragraphs).
* They also provide semantic information (e.g. where
emphasis should be placed, the definition of any
acronyms used, when given text is a quotation).

**2. Introducing CSS**
* CSS allows you to create rules that specify how the content of
an element should appear
* CSS treats each HTML element as if it appears inside
its own box and uses rules to indicate how that
element should look.
* Rules are made up of selectors (that specify the
elements the rule applies to) and declarations (that
indicate what these elements should look like).
* Different types of selectors allow you to target your
rules at different elements.
* Declarations are made up of two parts: the properties
of the element that you want to change, and the values
of those properties. For example, the font-family
property sets the choice of font, and the value arial
specifies Arial as the preferred typeface.
* CSS rules usually appear in a separate document,
although they may appear within an HTML page.

## ***JAVASCRIPT & JQUERY***
**1. Basic JavaScript Instructions**
* It is best to keep JavaScript code in its own JavaScript
file. JavaScript files are text files (like HTML pages and
CSS style sheets), but they have the . j s extension.
* The HTML script element is used in HTML pages
to tell the browser to load the JavaScript file (rather like
the link element can be used to load a CSS file).
* If you view the source code of the page in the browser,
the JavaScript will not have changed the HTML,
because the script works with the model of the web
page that the browser has created.
* A script is made up of a series of statements. Each
statement is like a step in a recipe.
* Scripts contain very precise instructions. For example,
you might specify that a value must be remembered
before creating a calculation using that value.
* Variables are used to temporarily store pieces of
information used in the script.
* Arrays are special types of variables that store more
than one piece of related information.
* JavaScript distinguishes between numbers (0-9),
strings (text), and Boolean values (true or false).
* Expressions evaluate into a single value.
* Expressions rely on operators to calculate a value

**2. Decisions and Loops” only up to the section on switch statements**
* JavaScript also has several built-in objects such as
String, Number, Math, and Date. Their properties and
methods offer functionality that help you write scripts.
* Conditional statements allow your code to make
decisions about what to do next.
* Comparison operators (===, ! ==, ==, ! =, <, >, <=, =>)
are used to compare two operands.

## ***How to Write a Git Commit Message***
* a commit message shows whether a developer is a good collaborator.
* Teams should first agree on a commit message convention that defines at least the following three things:
1. Style. Markup syntax, wrap margins, grammar, capitalization, punctuation. Spell these things out, remove the guesswork, and make it all as simple as possible. The end result will be a remarkably consistent log that’s not only a pleasure to read but that actually does get read on a regular basis.
2. Content. What kind of information should the body of the commit message (if any) contain? What should it not contain?
3. Metadata. How should issue tracking IDs, pull request numbers, etc. be referenced?

* The seven rules of a great Git commit message
1. Keep in mind: This has all been said before.
2. Separate subject from body with a blank line
3. Limit the subject line to 50 characters
4. Capitalize the subject line
5. Do not end the subject line with a period
6. Use the imperative mood in the subject line
7. Wrap the body at 72 characters
8. Use the body to explain what and why vs. how