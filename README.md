
This application contains tiny scripts for time management when working on the command line.

# INSTALL
Use the following command:

```
source ./environment_setup
```

# LIST OF APPLICATIONS

** pomo-distlog **
How many times your distracted on the command line? Like oh I should call Tony this evening or buy cereal today. Instead of letting the command line go and write these distractions on a piece of paper (or smart phone) log them. This application accepts a line of words as an input and appends it to the log. List the logs by passing -l or flush the log by passing -f flag.

```
    $ pomo-distlog call Tony later today.
    $ pomo-distlog -l
    2015-11-01 17:12:19.830453 call Tony later today.

```
