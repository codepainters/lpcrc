lpcrc
=====

This tiny project is a Python rewrite of lpcrc tool, the LPC13xx checksum calculator.

Why rewrite an exisiting tool? Because:

 * I switch my host platforms frequently
 * recompiling lpcrc.c on each is silly 
 * there's Python everywhere I work
 
So now I can simply add lpcrc.py call to my Makefile, and I'm done. Enjoy!
