# Lab Report 3
For this report, I chose to expirement with the keyword "find." 
### First Option 
The first option I chose was using the -mtime -N use of find, to output all 
the files that have been modified within the past N days. I found this use on ChatGPT,
an online chat bot. 
![LastModified](-mtime_find1)
![LastModified](-mtime_find2)
The . in these command lines tells the terminal to search the current directory, and 
-mtime means modified time, and -N is the span of days in which it was modified
### Second Option
The second option I chose was to use the ! operator, which finds all the files/directories 
that do not match the criteria. I also found this alternate use using ChatGPT.
![!Operator](!2)
![!Operator](!1)
The -type d command searches for directories only. 
### Third Option 
The third option I chose was the alternate use of find, the size operator. The size operator
is paired with -/+NM, where N is the number of megabytes each file/directory should be checked. 
The + will return any file directory greater than N megabytes, and - will return and file less
than N megabytes. I found this alternate use here: https://linuxize.com/post/how-to-find-files-in-linux-using-the-command-line/
![SizeOper](sizebash)
![SizeOper](sizebash1)
### Fourth Option
The fourth option I chose was the -user option, but because this led to an enormous output, I shortened
it using the head keyword. -user outputs all the files belonging to the user, and head prints the first N lines
of the output.
![userop](user1)
![userop](user2)



