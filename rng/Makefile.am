lib_LTLIBRARIES = libinterflop_rng.la

libinterflop_rng_la_CFLAGS = -O3 -fno-stack-protector -I../$(top_srcdir)
libinterflop_rng_la_LDFLAGS = -flto -O3
if WALL_CFLAGS
libinterflop_rng_la_CFLAGS += -Wall -Wextra -g
endif
libinterflop_rng_la_SOURCES = \
    splitmix64.c \
    xoroshiro128.c \
    vfc_rng.c