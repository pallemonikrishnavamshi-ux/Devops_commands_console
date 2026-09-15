CC = gcc
CFLAGS = -Wall -Wextra -g -Iinclude -I../include

SRC = src/main_week4.c \
      src/process.c \
      ../src/input.c \
      ../src/parser.c

TARGET = bin/shellforge-week4

all: $(TARGET)

$(TARGET):
	mkdir -p bin
	$(CC) $(CFLAGS) $(SRC) -o $(TARGET)

run: $(TARGET)
	./$(TARGET)

clean:
	rm -rf bin
