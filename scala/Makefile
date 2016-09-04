.PHONY: all clean

SCALAC=scalac

all: hw.class

hw.class: hw.scala
	${SCALAC} $?

clean:
	rm -f hw*.class *.orig
