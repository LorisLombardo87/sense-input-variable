# sense-input-variable

Input box for sense variables.
The user can modify the content of a variable by editing this input.

#Configuration
this extension need 7 parameter for working:

variable name: the name of the variable to controll

type: number or string.

title: a string that tells the user what is the variable.

help text: a string that help the user.

text to add before/after input: a useful parameter for defining UM ov the variable or similar info.

disable input: if it is empty the user can modify the value other whise it is not possible. it could be an expression ex: =if(getPossibleCount(field)=1,'',true())

