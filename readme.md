# Example 1
`make hello`

`make hallo`

`make bonjour`

Run each of these in the terminal and see what the output would be. What does it do?


# Info:
A makefile consists of these elements:
```
targets: prerequisites
    command
    command
    command
```


# Example 2

We can create folders, and put files in them.

Try `make folder`. What happened?

Try `make remove`. What happened?

Try `make stuff`. What happened?

# Example 3
If we run `make TARGET` and the target doesn't create a file, then running the command again
and again will result in the exact same output as before.

If the make command creates a file, then it will not run again if we repeat the command,
because the file of the same name has been created and now exists.

# Example 4
We can use variables to refer to multiple targets. 
Try the commands and see what they do!