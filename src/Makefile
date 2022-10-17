CC=gcc
CFLAGS=-std=c11 -pedantic -Wall -Werror -Wextra -D_FORTIFY_SOURCE=2 -O3 -fPIC -fstack-protector-all -pie -s
LDFLAGS=-lgmp -lsqlite3


digital-seconds-ago: digital-seconds-ago.c
	$(CC) $(CFLAGS) $(LDFLAGS) -o $@ $^

clear:
	rm digital-seconds-ago
