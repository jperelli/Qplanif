Qplanif
=======

Simulador de planificacion de la CPU

Compilacion
-----------

**Prereqs:**

sudo apt-get install libqt4-dev libqt4-qt3support flexc++ bison

**Comp:**

cd src

bison input.y

flex -o linput.c linput.l

cd ../bin

qmake-qt4 Makefile

make

Ejecución
---------

cd src

./bin

Creditos
========

Versión original:Ismael Ripoll y Sergio Saez

Adaptación a qt3/qt4: Julián Perel

LICENCIA
========

GNU GPL
