# Ft_printf

`ft_printf()` es una función que recrea el comportamiento de `printf()`, que seguramente ya conoces de la librería estándar de C. Sirve para imprimir texto en pantalla con diferentes formatos, como números, caracteres y direcciones de memoria. 🎨🔧📊

## 📥 Clonacion del repositorio

```sh
git clone https://github.com/Daniel-Escamilla/Prinft.git
cd Prinft
```

## ⚙️ Compilación

```sh
make
```

Esto creará el archivo `libftprintf.a`.

## 🛠️ Flags del Makefile

-   `make` → Compila la librería.
    
-   `make clean` → Borra los archivos objeto generados.
    
-   `make fclean` → Borra los archivos objeto y la librería `libftprintf.a`.
    
-   `make re` → Borra todo y recompila desde cero.
    

## 🚀 Uso de la librería

Para utilizar `ft_printf()` en tu código, inclúyelo de esta forma:

```c
#include "ft_printf.h"

int main()
{
    ft_printf("Hola, %s!\n", "mundo");
    return 0;
}
```

```sh
gcc -o programa main.c libftprintf.a
```

## 📌 Notas Importantes

-   El código se compila con `gcc` usando las opciones `-Wall -Wextra -Werror` para evitar errores.
    
-   Puedes revisar `ft_printf.h` para ver todas las funciones disponibles y cómo usarlas.
