# Whitespaces.scss

Whitespaces.scss is an scss file with auto generated margin and padding responsive classes for quick application in any project. 


Usage: 

Expanded syntax

`<margin/padding><device breakpoint>-<top/bottom/left/right>-<value upto 200>`

Compacted syntax

`<m/p><m/s>-<t/b/l/r>-<1..20>`

Declarations: 

mm ---> margin in medium device
ms ----> margin in small device
pm ----> padding in medium device
ps -----> padding in small device

mm-t-<value> -----> margin-top: <value>; for medium screen
mm-t-<value> -----> margin-top: <value>; for medium screen
  
ps-r-<value>.  ------> padding-right: <value> for small screens

Examples. 

````
.m-t-10, mm-t-20, ps-t-10 
````
