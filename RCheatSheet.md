##R Cheat Sheet

####Table Of Contents
http://www.personality-project.org/R/r.commands.html

-  [Help Commands](#help)
-  [Package Commands](#package)
-  [Inspecting Variables](#input)
-  [Moving Around ](#moving)
-  [Data Manipulation](#data)
-  [Statistics and transformations](#statistics)
-  [Graphics](#graphics)



### <a name="help"></a>Help Commands 

**Find out more about a function**

```{r}
[SYN] ?functionName or help(functionName)

[EX] ?rnorm or help(rnorm)

```

**Learn about the different ways to use a function**

```{r}
[SYN] example(functionName)

[EX] example(rnorm) 
```

**Display the arguments of a function**

```{r}
[SYN] args(functionName)

[EX] args(rnorm)

```              

**Search through R's help documentation for a specific term**
```{r}
[SYN] help.search("your search term")

[Ex] ?rnorm  or help(rnorm)
```

### <a name="package"></a> Package Commands

**Install a Package**
```{r}
[SYN] install.packages("package name")

[EX] install.packages('rnorm')
```

**Find installed packages**
```{r}
   installed.packages()
```


### <a name="input"></a> Inspecting Variables

**Find the Class of a variable**
```{r}
x <- 3
class(x)

```



assign()

Generating regular sequences
2*1:15
seq()
rep()
paste()

### <a name="moving"></a> Moving Around Commands
### <a name="data"></a> Data Manipulation Commands
###<a name="statistics"></a> Statistics and Transformations Commands
### <a name="graphics"></a> Graphics Commands

