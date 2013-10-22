LDFLAGS=-luv
NAME=$(shell basename $(CURDIR))

build:
	$(CC) -o $(NAME).o $(NAME).c $(LDFLAGS)

custom:
	$(CC) -o $(NAME).o ../../libuv-custom/build/Release/libuv.a -I../../libuv-custom/include $(NAME).c

clean: 
	rm -Rf *.o