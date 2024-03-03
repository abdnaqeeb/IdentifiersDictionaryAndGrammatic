# Boolean type

A boolean variable can hold either true or false values.
As a general convention a name of a boolean variable should be interpreted as a yes or no question.
For example the variable `hidden` should be interpreted to "Is this hidden?"

To elicit a boolean variable name we start by phrasing a yes/no question.

Yes/No questions starts with one of these helping verbs:
- do, does, did
- has, have, had
- is, was, are, were, am
- shall, should
- will, would
- can, could
- may, might
- must

The subject can be any object name or can be the current class object.
If we refer to the current class object we use the word "this". An example of this, "Is ***this*** hidden?".
In most cases we eliminate "this" from the boolean variable name.
If we end with `Is <adj>` like `Is hidden` we eliminate the help verb `Is` and we end up with a single word to represent the boolean variable name `hidden`.

We avoid using some words if that does not disturb the meaning of the boolean varaible name. These words enclude: of, the.

## Examples

will this component update? ---> willUpdate
did student pass the exam? ---> didStudentPassExam
should the menu component re-render? ---> shouldMenuRerender
is the list loading? ---> isListLoading
is this loading? ---> isLoading ---> loading
can this be removed? ---> canBeRemoved
was this active? ---> wasActive
is this active ---> isActive ---> active



