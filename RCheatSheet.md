---
output:
  html_document:
    highlight: textmate
    number_sections: yes
    theme: cerulean
    toc: yes
---
##R Cheat Sheet

-  [Help Commands](#help)
-  [Package Commands](#package)
-  [Inspecting Variables](#input)
-  [Moving Around ](#moving)
-  [Data Manipulation](#data)
-  [Statistics and transformations](#statistics)
-  [Graphics](#graphics)



### <a name="help"></a>Help Commands 

***Find out more about a function***

	 help(functionName)
	   > ?rnorm  OR > help(rnorm)
	
***Learn about the different ways to use a function***

	 example(functionName)
	   > example(rnorm) 
	

***Display the arguments of a function***

    args(functionName)
`> args(rnorm)`
	              

***Search through R's help documentation for a specific term***
	
    help.search("your search term")

`> ?rnorm or help(rnorm)`
	
### <a name="package"></a> Package Commands

***Install a Package***

	 install.packages('package name')	  
	  > install.packages(rnorm)
	  

***Find installed packages***

``` > installed.packages()```


### <a name="input"></a> Inspecting Variables

***Find the Class of a variable***
	
`> class(x)`


***Checking and Changing Classes***

``` > is.character("red,yellow")```

``` > is.logical(TRUE)```

``` > is.numeric(3)```

***View complete list of is functions***

``` > ls(pattern="^is",baseenv()) ```

### <a name="moving"></a> Moving Around Commands
### <a name="data"></a> Data Manipulation Commands
###<a name="statistics"></a> Statistics and Transformations Commands
### <a name="graphics"></a> Graphics Commands


http://www.personality-project.org/R/r.commands.html