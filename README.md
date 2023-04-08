# skdev
A skript that can:

* Check / Set / Clear Variables
* Check / Clear Lists

It isn't that much, but it **really helps** when you can just check a variable with a command rather than making a check in the skript
## Guide
 This guide will help you understand the skript more and how to use it.
### What is the skript helping with
 The skript allows for quick checking, setting and clearing of variables which are declared like this {_your variable name_} and  
 it can also check and clear lists which are declared like this {_your list name_::*}.  
 **! Warning !** You **can't** do these thing with temporary list and variables which are delcared the same way, but with an underscore. For example: {__your variable/list name_}
### Basic skript usage
This part of the guide is about basic skript usage if you forget any of the commands listed you can do _/skdev help_ which will send you the help commands for variables and lists
#### Variables
[ ] is used for showing where to put your variable don't put those in when you are writing the command  
( ) are used to show opptional things ! You don't need to use them !

* Check:

  You can check variables with: **/skdev variable check [_your variable name_]**
  
  It will send you what is the value for this variable
* Set:

  You can set the variables with: **/skdev variable set [_your variable name_] [_new variable value_] (string/text)**  
  
  It will send you the old value and new variable value.  
  The last argument is used only in situations if you want to set the variable with a number or boolean, but it has to be a text for that you can use either string or text. For example: You want to set the variable to 1, but as a text you would need to add text as the last argument
  
* Clear

 You clear the variables with: **/skdev variable clear [_your variable name_]**
 It just clears the variable.
 
#### Lists
[ ] is used for showing where to put your variable don't put those in when you are writing the command  
( ) are used to show opptional things ! You don't need to use them !

* Check:
  You can check variables with: **/skdev variable check [_your lists name_]**
  
  It will send you what is the value for this variable
 You can check lists with /skdev list check
 
