TARGET  := matchengine
INCS = -I ../network -I ../utils
LIBS = -L ../utils -lutils -L ../network -lnetwork -Wl,-Bstatic -lev -ljansson -lmpdec -lssl -lcrypto -lhiredis -lz -Wl,-Bdynamic -lm -lpthread -ldl -lmysqlclient -lrdkafka
include ../makefile.inc
