all: diary

diary: memo.o calendar.o main.o
	gcc -o diary memo.o calendar.o main.o

memo.o: memo.c
	gcc -Wall -Wextra -o  memo.o -c memo.c

calendar.o: calendar.c
	gcc -Wall -Wextra –o calendar.o -c calendar.c

main.o: main.c
	 gcc –Wall –Wextra –o main.o -c  main.c

clean:
	 rm –rf *.o diary

