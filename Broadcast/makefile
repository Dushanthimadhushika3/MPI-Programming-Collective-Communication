EXECS=Broadcast
MPICC?=mpicc

all: ${EXECS}
Broadcast: bcast.c
	${MPICC} -o Broadcast bcast.cpp

clean:
	rm -f ${EXECS}
