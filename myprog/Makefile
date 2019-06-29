include ../Makefile.inc

EXE = myprog.c

all : myprog.c 
	cc -c myprog.c
clean : 
	${RM} ${EXE} *.o

showall :
	@ echo ${EXE}

${EXE} : ${TLPI_LIB}
