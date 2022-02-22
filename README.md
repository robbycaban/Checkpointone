# Checkpointone
5. What can we use to save a value for later use in our code? Provide an example.
How do I save values for later use?

In Python, can give a value an easy-to-remember label and use it again and again.
especially useful if the value itself is long and tricky to type out.
Programmers refer to these labels as variables.

friendly_greeting = "Hello World"

print(friendly_greeting)

On the first line of this program, we are using = to assign the value "Hello World" to the variable friendly_greeting. If you were to add more lines to your program, you could refer to the String "Hello World" simply by using the variable name friendly_greeting.
6.On the first line of this program, we are using = to assign the value "Hello World" to the variable friendly_greeting. If you were to add more lines to your program, you could refer to the String "Hello World" simply by using the variable name friendly_greeting.

What can I do to prevent certain files and directories from being tracked by git?
git ignore
details: Step 1. Add the folder path to your repo's root .gitignore file.
path_to_your_folder/

Step 2. Remove the folder from your local git tracking, but keep it on your disk.
git rm -r --cached path_to_your_folder/

Step 3. Push your changes to your git repo.

