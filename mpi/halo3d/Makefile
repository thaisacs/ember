
CC=mpicc
CFLAGS=-O3 -std=c99
LIBS= ../../../kernel_stats/kernel_stats.o

halo3d: halo3d.c
	$(CC) $(CFLAGS) -o $@ $< $(LIBS)

clean:
	rm halo3d

