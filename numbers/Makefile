CC=gcc
CFLAGS = -Werror -Wall -Wno-unused-variable -g -O0
OBJ = ex3.o
TARGET = success

%.o : %.c $(HEADERS)
	$(CC) -c -o $@ $< $(CFLAGS)

$(TARGET): $(OBJ)
	$(CC) -o $@ $^ $(CFLAGS)

clean:
	rm -f $(OBJ) $(TARGET)
