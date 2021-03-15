Build RMI index:

`cargo run --release -- books_200M_uint32 my_first_rmi linear,linear 100`

Compile simple test program:

`g++ -std=c++17 -Wall -O3 -ffast-math -march=native main.cpp my_first_rmi.cpp -o test`