## HelloWorld-TC1033.2
# Alejandro Lizárraga Vizcarra
## Laboratorio - branch - commits - pull-request - merge - markdown

**bold text**

*italics*

1. Github
2. Método de calcular las frecuencias
3. Descargar los nuevos archivos de Series y Episodios

- Github
- Método de calcular las frecuencias
- Descargar los nuevos archivos de Series y Episodios

```c++
//
//  Reloj.hpp
//  ClaseReloj
//
//  Created by Alejandro Lizarraga on 10/11/21.
//

#ifndef Reloj_hpp
#define Reloj_hpp

#include <stdio.h>

class Reloj{
    public:
    //Metodo constructor
    Reloj();
    Reloj(int,int);
    
    //Metodos
    void setHora(int);
    void setMinutos(int);
    
    int getHora();
    int getMinutos();
    
    void muestra();
    void incrementaMinutos();
    
    private:
        int hora = 0;
        int minutos = 0;
};

#endif /* Reloj_hpp */
```
---
[markdownguide.org](https://www.markdownguide.org/cheat-sheet/)

[Pagina de Google](https://www.google.com)

![monkey](monkey.jpeg)

| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

- [x] Elote
- [ ] Agua
- [x] Carne
