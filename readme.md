![Diagram](https://github.com/c3joshzhang/cpp_cython_python/blob/master/diagram.png =250x)

to compile with c++: 
	gcc main.cc PyAdapter.cpp Exmaple.cpp -fopenmp -std=c++11 -O3 -lstdc++

to compile with cython: 
	python setup.py build_ext --inplace

