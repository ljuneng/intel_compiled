# intel_compiled
./configure CC=icx CXX=icpx FC=ifx F77=ifx --prefix=${INSTALL_DIR}
make
make check
make install
