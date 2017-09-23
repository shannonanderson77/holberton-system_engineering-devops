<h1>Readme</h1>

<h2>Shell I/O Redirection and Special Characters</h2>

<p>Redirecting the output of commands to files, devices, or the input of other commands.</p>

<ul>
<li>>		redirect standard output to a file</li>
<li>>>		append output to a file</li>
<li><		get standard input from a file instead of the keyboard</li>
<li>|		send output from one program to the input of another program</li>
<li>2>&1	redirect the error output to the standard output</li>
<li>/#		start of a comment</li>
<li>\		escape special characters</li>
<li>" "		whitespace, can be a tab, newline, vertical tab, form feed, carriage return or space</li>
<li>~		tilde, representation of home directory, ~/ means current users home directory otherwise takes username</li>
<li>!		negate</li>
<li>''		protect text inside so that it has a literal meaning</li>
<li>;		seperates multiple commands on the same line</li>
</ul>

<p>Filters take standard input, performs an operation and then sends results to standard output. Frequently used with pipelines.</p>

<ul>
<li>sort	sorts standard input then outputs the sorted result on standard output</li>
<li>uniq	given a sorted stream of data from standard input, removes duplicate lines of data</li>
<li>grep	examines standard input for a specified pattern of characters and outputs every line that contains those characters</li>
<li>head	outputs the first few lines of its input (useful for getting header of a file)</li>
<li>tail	outputs the last few lines of its input (useful for getting most recent entries from a log file)</li>
<li>cat		read file and output to standard output</li>
<li>tr		translates characters (used to perform upper/lowercase conversions or converting DOS text files into Unix style text files)</li>
<li>rev		reverse lines characterwise</li>
<li>cut		remove sections from each line of files</li>
<li>wc		print newline, word and byte counts for each file</li>
<li>passwd	change user password</li>
</ul>

<p>When combining commands and filters with redirections, the redirection must appear after the other options and arguments in the command.</p>

<ul>
<li>/etc/passwd - user account information,</li>
<li>/etc/shadow - secure user account information</li>
</ul>

<img src="https://www.holbertonschool.com/assets/holberton-logo-1cc451260ca3cd297def53f2250a9794810667c7ca7b5fa5879a569a457bf16f.png"/>
