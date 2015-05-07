CC = rpxc-gcc
#LIBS = -lpthread 
CFLAGS = -O2 -w
SRCS = PJ_RPI.c main.c
OBJS = PJ_RPI.o main.o

all : Blink

.c.o :
	${CC} ${CFLAGS} -c $< 

Blink : $(OBJS)
	$(CC) -o $@ $(OBJS) $(LIBS) -lm

clean:
	rm -f *.o *~ Blink
