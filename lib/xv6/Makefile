TOP_SRCDIR = ../..
include $(TOP_SRCDIR)/Makefile.common
CFLAGS+= -D_POSIX_SOURCE

all: chown.o chmod.o creat.o stat.o getuid.o umask.o mkfifo.o \
        time.o utime.o rename.o rmdir.o usys.o oldmalloc.o oldprintf.o \
	tcgetattr.o opendir.o fstat.o access.o sleep.o _start.o misc.o \
	signal.o exec.o

clean:
	rm -f *.o
