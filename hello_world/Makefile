CC=gcc
CFLAGS = -Werror -Wall -g -O0
OBJ = hello.o
TARGET = hello.out

%.o : %.c $(HEADERS)
	$(CC) -c -o $@ $< $(CFLAGS)

$(TARGET): $(OBJ)
	$(CC) -o $@ $^ $(CFLAGS)

clean:
	rm -f $(OBJ) $(TARGET)
