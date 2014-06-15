OBJ=fastlz.c
OBJNAME=libfastlz
VERSION=1.0
CFLAGS=-Wall
LFLAGS=-shared -fPIC

all:
	gcc ${OBJ} -o ${OBJNAME}-${VERSION}.so ${CFLAGS} ${LFLAGS}
	mv ${OBJNAME}-${VERSION}.so ../../
