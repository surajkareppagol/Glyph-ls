CC:=gcc

all: build run

build: list.c main.c
	@${CC} -c list.c
	@${CC} -c args.c
	@${CC} -c main.c
	@${CC} -o gls.out main.o list.o args.o

run: gls
	@./gls

clean:
	@rm main.o list.o args.o gls.out
