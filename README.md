shakespeare
===========

Prints a Shakespearean Sonnet when you Open a Terminal.

There are multiple sonnets that don't have 14 lines.

Sonnet 126 has 12 lines, for example.

These are handled by assuming a sonnet will have at most 20 lines, breaking at the next number seen, and using the 4/4/4/2 spacing regardless of the number of lines.

# How to run
1. Place the shakespeare folder in a directory called shakespeare
2. Modify .bashrc to include a call to shakespeare (./shakespeare/shakespeare)
3. If you want to use text-to-speech then install Festival (or do your own thing)

# Credits
* I use a text file with Shakespearean Sonnets pulled from Project Gutenberg
