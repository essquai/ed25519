SOURCES = test.c ../src/add_scalar.c ../src/fe.c ../src/ge.c               \
          ../src/key_exchange.c ../src/keypair.c ../src/sc.c ../src/seed.c \
          ../src/sha512.c ../src/sign.c ../src/verify.c
CFLAGS  = -I../src

all:  test

test: $(SOURCES)
	$(CC) -o test $(CFLAGS) $(SOURCES)

