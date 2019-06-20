TARGET  := matchengine.exe
INCS = -I ../network -I ../utils -I /usr/local/include
LIBS = -L/usr/lib64/mysql -L ../utils -lutils -L ../network -lnetwork -Wl,-Bdynamic -lev -ljansson -lmpdec -lmysqlclient -lz -lrdkafka -lssl -lcrypto -lhiredis -Wl,-Bdynamic -lm -lpthread -ldl
include ../makefile.inc
