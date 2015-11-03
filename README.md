# sense-input-variable

Allow the user to set the value of a variable in an options set

#Configuration
this extension need 7 parameter for working:

variable name: the name of the variable to controll

title: a string that tells the user what is the variable.

help text: a string that help the user.

input type: if drop down is selected the user must select a value from a drop down list. if checkboxes is selected all the options are draw in a list, useful with less options.

text to add before and after the input.

disable input: if it is empty the user can modify the value other whise it is not possible. it could be an expression ex: =if(getPossibleCount(field)=1,'',true())

