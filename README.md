# code_tricks_pitfalls
## HPRC Grace
**Supported IDE**: VS code; PyCharm \
**VS code**:



--
### Install mmseqs with cmake
```bash
ml GCCcore/12.3.0 GCC/12.3.0 CMAKE/3.26.3
CC=gcc-12
CXX=g++-12
cmake -DCMAKE_BUILD_TYPE=RELEASE -DCMAKE_C_COMPILER=/sw/eb/sw/GCCcore/12.3.0/bin/gcc -DCMAKE_INSTALL_PREFIX=. ..
