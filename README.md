# Communication Project: Terminal Streams
This project explains terminal streams and code operations for terminal streams.

This is the final project of Communications for Analytics Course at the University of San Fransicso.

#  Introduction of Streams:
UNIX(terminal) system has a standard stream pattern, input-command-output stream. While programming, we can use some commands to manipulate the streams and redirect the input/output of the program. We use “|”, called pipe, passing the output of one program to the input of another program, i.e. ls | wc, passing the listed files to word count. Also, we use “>/<” sign to save the output to a file or take a file as input to a program, i.e. python foo.py > result.txt, saving the output of foo.py to the result.txt file. The streams and i/o redirection are the foundation of terminal operation that helps us more efficiently run the program as well as combine programs and files.

For detailed usage, see [code example](https://github.com/mgeg/communication-streams/blob/main/Streams.ipynb)

Group members: [Wei](https://github.com/weihe13),  [Xinyue](https://github.com/mgeg),  [Yoli](https://github.com/hereisyoli)

Reference:  [Streams/pipes/redirection in the terminal](https://github.com/parrt/msds692/blob/master/notes/streams.pdf)
