# Author: Mehul Prajapati

EXEC=getChildElem
INCLUDES=-I/usr/include/libxml2 -I/usr/local/include/libxml2
CC=gcc

# Main Rule
all:
	@echo "Building source file"
	${CC} -o ${EXEC} ${INCLUDES} $(wildcard *.c) -lxml2
clean:
	@echo "Removing executable"
	@rm ${EXEC}
