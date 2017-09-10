Readme

Shell I/O Redirection and Special Characters

Redirecting the output of commands to files, devices, or the input of other commands.

\> - redirect standard output to a file"nl"
\>> - append output to a file"
\< - get standard input from a file instead of the keyboard"
\| - send output from one program to the input of another program
\2>&1 - redirect the error output to the standard output
\# - start of a comment
\\ - escape special characters
\" " - whitespace, can be a tab, newline, vertical tab, form feed, carriage return or space
\~ - tilde, representation of home directory, \~/ means current users home directory otherwise takes username
\! - negate
\'' - protect text inside so that it has a literal meaning
\; - seperates multiple commands on the same line

Filters take standard input, performs an operation and then sends results to standard output. Frequently used with pipelines.

sort - sorts standard input then outputs the sorted result on standard output
uniq - given a sorted stream of data from standard input, removes duplicate lines of data
grep - examines standard input for a specified pattern of characters and outputs every line that contains those characters
head - outputs the first few lines of its input (useful for getting header of a file)
tail - outputs the last few lines of its input (useful for getting most recent entries from a log file)
cat - read file and output to standard output
tr - translates characters (used to perform upper/lowercase conversions or converting DOS text files into Unix style text files)
rev - reverse lines characterwise
cut - remove sections from each line of files
wc - print newline, word and byte counts for each file
passwd - change user password

When combining commands and filters with redirections, the redirection must appear after the other options and arguments in the command.

\/etc\/passwd - user account information
\/etc\/shadow - secure user account information