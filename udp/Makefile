
LDFLAGS = -lpthread

.PHONY : clean

udp : udp.o
	$(CC) -o $@ $^ $(LDFLAGS)


clean :
	rm -f *.o udp
