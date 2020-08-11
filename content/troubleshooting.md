# knowlege base
A compact list of tools and strategies useful when working in IT.

## Inventory 
A full description of all of the hardware , software, licenses available at your disposal with all the information, description and specifications that might become in handy to have.


## Ticket System
The following is a ticket system design to document the debugging proccess used when encountering errors and misconfigurations in a daily use. This system is intended for personal use and might struggle to scale for more complex organizations. Some of the issues this system does not take into account and lack the capabilities to deal with can be found [here]().

### Setting up the rules
__Structure:__ Each ticket must have the following components: an identification code, a summary, an status and short description of the debuggin process. Some other components that become important in a complex organization but are not implemented in this particular system are the following: priority, date of filing, channel used to file, entity responsable, feed back and costumer satisfaction.    

__identification code__: is an numberic code that uniquely identifies each ticket filed, it is composed of two parts: The __category__ part, a four digit number each one  representing a level, inspired by the Dewey Decimal Classification system (DDC) would ticket and __id number__ and 

Recategorize 
No ticket gets eleminated 


periodic archiving 

0000-00

\<OS\>



1. OS:
0 -> undefined
1 -> Windows
2 -> Linux

2. Aplication type:
1 -> System 
Networking

2 -> Office
3 -> Programming tools

* __0****__
    


### Ticket list

* __0001 dll missing:__ when openning Rstudio after a installing a new package ```xlsx``` and loading it through  ```library(xlsx)``` error rJava.dll missing. R version 4.0 

![error message](./media/images/ticket-0001-dll-library-missing.png)

the .dll file need to be register back __did not work__ 
    
    regsvr32 /u "D:/programacion/documentation/R-4.0.0/library/rJava/libs/x64/rJava.dll"

depurate the dll file

update R from version 4.0 version to 4.2 load  ```library(xlsx)```
    
    error: Your java version is 14.  Need 1.5.0 or higher.

update java  __solved__

* 0002: disable read only
 
    attributes disk clear readonly




## power shell
scprits has no permission, tempora comment profile.ps1

```
#region conda initialize
# !! Contents within this block are managed by 'conda init' !!
#(& "D:\programacion\anaconda\Scripts\conda.exe" "shell.powershell" "hook") | Out-String | Invoke-Expression
#endregion

```


