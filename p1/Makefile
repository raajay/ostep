compile:
	gcc -o genvar genvar.c -Wall -Werror
	gcc -o dumpvar dumpvar.c -Wall -Werror

data: compile
	./genvar -s 0 -n 100 -m 32 -o /tmp/outfile

text:
	./dumpvar -i /tmp/outfile
