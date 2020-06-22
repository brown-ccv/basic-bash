## Bash Basics


# Important concepts

### Bash is a scripting language

A script it a list of things for the computer to do

Scripts allow you to automate work.

Scripts are text files.  To tell the computer that the file is a 
bash script, put the following on the first line

````
#!/bin/bash
````


### Running a script

````
bash my_script.sh
````

You can make the script *exectuable*

````
chmod +x my_script.sh

Then execute the script like this:

````
./my_script.sh
````


### Debugging options

Verbose:

````
#!/bin/bash -v
````

# Exercises

1. Environment variables

Run the script `hello`.  What happens? Take a look at the script with `cat hello`
Which environment variable is being used here?
List all the enviroment variables in your session with `env`

2. Arguments

Arguments are inputs given to a script. Run the script `arguments` with some arguemnts, for example:
`bash arguments one two dog cat fish`
*Extra credit*: Can you change the script to check if there are at least two arguments?

3. If statements
If statements are logic you can use to make your script do different things depending on the if condition.  `example_if` takes a number as an argument and prints out if the number is less than or greater than 3. 
`bash example_if 55`

*Extra credit*: Can you change the script to only accept numbers?

4. Case statements

Case statements are an alternative to writing nested if statements (ifs inside ifs inside ifs ...).  `case` is an example case statement.  `case` also contains an infinite while loop. The case statement checks the input from the keyboard.  If the input is `bye` the break is executed and code exits the infinite while loop.  



# Reources:

The [bash manual](https://www.gnu.org/software/bash/manual/html_node/index.html) 


