# Just a bunch of practice stuff for the Data Structures course

## Getting Started
Luckily, I've already got gcc on my macbook. So you can write code as seen in 
main.c. To create that all I did was make a text file named main.c and wrote 
that code in it. Then when you want to compile it write

$ gcc -Wall -o <name\_of\_output> main.c    
    
The -W option is for Warnings when compiling, no idea what the -all does, that's just what [the guy in this youtube video did](https://youtu.be/FJSeiyOmZzM) so I just followed suit. The -o is for the output so that it knows what to name the executable. That's why the <name\_of\_output> variable is needed, it's an argument to -o. Then finally we pass the file we want to compile.

To execute whatever you named your output file, write

$ ./<name\_of\_output>
