# sfsymbols
SF Symbols de Apple, íconos en svg listos para usar en proyectos web

El archivo css sfsymbols.css contiene las propiedades para incrustar correctamente los íconos
## Contenido
La librería consta de los siguientes elementos:

```
. (directorio raíz)
├── icons (carpeta de iconos)
│   ├── contiene los más de 4 mil iconos en formato svg
└── sfsymbols.css (css constructor de la librería)
```
## Uso
- Copia toda la carpeta "sfsymbols" a tu proyecto, en donde te de la gana.
- Importa en tu sitio el archivo sfsymbols.css
- Se trabaja sobre la etiqueta ``` <i> ```
- Se declara por medio de clases
  - la clase **icono** es el padre
  - el nombre del archivo .svg es la clase hija **square.and.arrow.up**
- Primero, tenemos que crear la clase del icono que quieres usar hasta el fondo  del archivo css
  ```
  i.icono.square.and.arrow.up:before {
    content: url('./icons/square.and.arrow.up.svg');
  }
- Segundo, creas la clase en el html
- y se escribe de la siguiente forma:
  ```
  <i class="icono square and arrow up"></i>
Y con eso tienes listo todo.

### Se espera que para el futuro no se tenga que hacer todo esto, ya que son 5mil iconos, y estoy creando aún el archivo de fuente otf para facilitar las cosas.
En una siguient actualización iré explicando los estados posibles que tienen los iconos, si no es que lo descubren primero.
