
# TE - Calculadora Simplificada

Este é o código exemplo do trabalho usando TDD (*Test Driven Development*) com o framework C++ [Catch2](https://github.com/catchorg/Catch2/tree/v2.x).


O framework Catch2 consegue ser utilizado apenas com o arquivo header [catch.hpp](catch.hpp) sem necessidade de instalação.

**NÃO MODIFIQUE OS TESTES** 

Todos os testes estão prontos no arquivo [calculadora.cpp](calculadora.cpp). A compilação e teste pode ser feita com os comandos:
```
$ g++ -Wall -std=c++11 -o calc calculadora.cpp 
```

A saída resumida do teste (código exemplo):
```
$ ./calc --reporter compact --success
calculadora.cpp:73: failed: c.fim() == true for: false == true
calculadora.cpp:82: failed: c.fim() == true for: false == true
calculadora.cpp:91: failed: c.fim() == true for: false == true
calculadora.cpp:100: failed: c.fim() == true for: false == true
calculadora.cpp:109: failed: c.fim() == true for: false == true
calculadora.cpp:118: failed: c.fim() == true for: false == true
calculadora.cpp:127: failed: c.fim() == true for: false == true
calculadora.cpp:136: failed: c.fim() == true for: false == true
calculadora.cpp:145: failed: c.fim() == true for: false == true
calculadora.cpp:154: failed: c.fim() == true for: false == true
Failed all 10 test cases, failed all 10 assertions.
```
