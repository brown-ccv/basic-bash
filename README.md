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

# Reources:

The [bash manual](https://www.gnu.org/software/bash/manual/html_node/index.html) 


