# sense-input-variable

Allow the user to set the value of a variable in an options set

#Configuration
this extension need 7 parameter for working:

variable name: the name of the variable to controll

option values: it must be a list of options separed by commas. it could be the result of an expression, ex: =Concat(distinct field,',') or a comma separed list of values ex: 1,2,3,4 .

option descriptions: it must be a list of options descriptions separed by commas, this array must be ordered in the samy way as the option values array. it could be the result of an expression. if not present whil be used the value as description.

title: a string that tells the user what is the variable.

help text: a string that help the user.

input type: if drop down is selected the user must select a value from a drop down list. if checkboxes is selected all the options are draw in a list, useful with less options.

disable input: if it is empty the user can modify the value other whise it is not possible. it could be an expression ex: =if(getPossibleCount(field)=1,'',true())

