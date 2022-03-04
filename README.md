# Tesseract-5

compiled as single threaded

```
   cd tesseract
   ./autogen.sh
   mkdir -p bin/release
   cd bin/release
   ../../configure --disable-openmp --disable-shared 'CXXFLAGS=-g -O2 -fno-math-errno -Wall -Wextra -Wpedantic'
   # Build tesseract and training tools. Run `make` if you don't need the training tools.
   make training
   cd ../..
```
