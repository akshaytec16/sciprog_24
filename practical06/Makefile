# Compiler and flags
CC = gcc
CFLAGS = -Wall -g

# Target executable
TARGET = matrix_multiply

# Source files and object files
SRC = main.c mathmult.c
OBJ = main.o mathmult.o

# Default target
all: $(TARGET)

# Rule to create the target executable
$(TARGET): $(OBJ)
	$(CC) $(CFLAGS) -o $(TARGET) $(OBJ) -lm  # Link with math library

# Rules to compile each source file into an object file
main.o: main.c
	$(CC) $(CFLAGS) -c main.c

mathmult.o: mathmult.c
	$(CC) $(CFLAGS) -c mathmult.c

# Clean up generated files
clean:
	rm -f $(OBJ) $(TARGET)
