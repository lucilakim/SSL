# 00-CHelloWorld

* Compilador seleccionado: Apple clang
* Version del compilador: 15.0.0
* Versión de C que el compilador compila: C17

para trabajar con C23 usare el flag `-std=c2x`

Comandos utilizados para obtener la informacion:
```sh
gcc --version

Apple clang version 15.0.0 (clang-1500.3.9.4)
```

```sh
echo | cc -dM -E -x c - | grep __STDC_VERSION__

#define __STDC_VERSION__ 201710L
```