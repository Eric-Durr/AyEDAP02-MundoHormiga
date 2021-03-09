# AyEDA P03 - Mundo Hormigas


## Uso

### **Compilación del ejecutable**

```bash
$ make
```

### **Ejecución del programa**

**Para un entorno básico (con la hormiga por defecto en el centro)**

```bash
$ ./mundo_hormigas 
```

### **Lanzamiento de los tests**

```bash
$ make test
```

Se compila y ejecuta el conjunto de tests para luego ejecutarlos, de suceder satisfactoriamente debe aparecer lo siguiente por terminal:

```bash
Making tests: mundo_hormigas_test
g++ -o mundo_hormigas_test ./src/entorno.cpp ./src/hormiga.cpp ./test/includer.test.cpp
./hormiga_langton_test
===============================================================================
All tests passed (38 assertions in 2 test cases)
```

También se puede ejecutar un despliegue detallado de los tests si ya se ha lanzado el comando anterior:

```bash
$ ./mundo_hormigas_test -s
```

## Licencia

[MIT](https://choosealicense.com/licenses/mit/)

## Autoría

- Eric Dürr Sierra - [alu0101027005](alu0101027005@ull.edu.es)
