modules-Bisque
==============

iRODS module for Bisque integration

Installation:
-------------
cd $IRODSHOME/modules
git clone git://github.com/hajaalin/modules-Bisque.git Bisque

cd $IRODSHOME
rm server/re/include/reAction.h
./scripts/configure --enable-Bisque
make reaction
make
 
