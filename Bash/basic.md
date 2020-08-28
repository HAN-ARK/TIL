# Shell Script
```bash
#! /bin/bash
echo "Hello Bash" 
```  
#### The different types of shells  
* bash(Bourne-Again Shell)  
* sh(Bourne Shell)  
* csh(C stlye Shell)  
* zsh  

#### The basics 
```bash
# In the beginning of the bash shell script, it is required to write 
#! /bin/bash

#In order to print values
echo "Hello World"

#How to use variables
#variable=value, note that there is no space
intro="This is bash shell script"
echo "$intro"

#How to input values
echo -n "Do you have any question : "
read input
echo "You asked this: $input"

#Calculation requires expr
a=4
b=2

#Addition
add=`expr $a + $b`

#Subtraction
sub=`expr $a - $b`

#Multiplication
mul=`expr $a \* $b`

#Division
div=`expr $a / $b`

```



