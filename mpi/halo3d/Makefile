
CC=mpicc
CFLAGS=-O3 -std=c99
LIBS= ../../../../utils/obj/*.o

halo3d: halo3d.c
	$(CC) $(CFLAGS) -o $@ $< $(LIBS)

clean:
	rm halo3d

