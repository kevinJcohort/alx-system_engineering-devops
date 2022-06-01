0. <o> - alias ls="rm *" - script that creates an alias.
1.Hello you - echo "hello $USER" - Create a script that prints hello user, where user is the current Linux user.
2.The path to success is to take massive, determined action - export PATH=$PATH:/action - Add /action to the PATH. /action
3.If the path be beautiful, let us not ask where it leads - echo $PATH | tr -s ":" "\n" | wc -l - Create a script that counts the number of directories in the PATH.
4.Global variables - printenv - Create a script that lists environment variables. 
5.Local variables - set - Create a script that lists all local variables and environment variables, and functions.
6. Local variable - BEST="School" - Create a script that creates a new local variable.
7. Global variable - export BEST="School" - Create a script that creates a new global variable.
8. Every addition to true knowledge is an addition to human power - echo "$((TRUEKNOWLEDGE+=128))" - Write a script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.
9.Divide and rule - echo $((POWER/DIVIDE)) - Write a script that prints the result of POWER divided by DIVIDE, followed by a new line. 
10.10. Love is anterior to life, posterior to death, initial of creation, and the exponent of breath - echo $((BREATH**LOVE)) - Write a script that displays the result of BREATH to the power LOVE
11.There are 10 types of people in the world -- Those who understand binary, and those who don't - echo "$((2#$BINARY))" - Write a script that converts a number from base 2 to base 10.
12.Combination - printf "%s\n" {a..z}{a..z} | grep -v "oo" - Create a script that prints all possible combinations of two letters, except oo.
13.Floats - printf "%.2f\n" $NUM - Write a script that prints a number with two decimal places, followed by a new line.
