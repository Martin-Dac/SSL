SOURCE = hello.c
BIN = hello.exe
OBJ = hello.o
CC = gcc
CFLAGS = -std=c2x

$(BIN): $(OBJ)
	$(CC) $(OBJ) -o $(BIN) $(CFLAGS)

$(OBJ): $(SOURCE)
	$(CC) -c $(SOURCE) -o $(OBJ) $(CFLAGS)

run: $(BIN)
	./$(BIN) > output.txt