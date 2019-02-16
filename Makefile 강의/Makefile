CC = gcc
TARGET = app.out
OBJS = main.o kor.o usa.o

all : $(TARGET)

$(TARGET) : $(OBJS)
	$(CC) -o $@ $^

.c.o:
	$(CC) -c -o $@ $<
