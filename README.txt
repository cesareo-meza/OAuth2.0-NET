A continuaci�n se deja el c�digo mostrado en este KP. Se requiere Visual Studio 2012

[Repositorio de git OAuth2.0-NET | https://github.com/cesareo-meza/OAuth2.0-NET.git]

Para usar el codigo es necesario hacer un par de ajustes para que corra en su ambiente propio,

1. En la pesta�a de propiedades del proyecto, cambiar la URL actual (https://localhost:44301) y poner una URL sin https la que sea

2. En las propiedades del proyecto, las que salen al presionar F4 buscar el campo cambiar la propiedad SSL enabled a false y ejecutar la aplicaci�n

3. Regresar la propiedad mencionada en el punto 2 y ponerla en true, esto hace que se genere una nueva URL SSL, copiar esta URL generada y ponerla en la propiedad cambiaba en el punto 1.

4. Habilitar una aplicaci�n de google y agregar la URL generada en el paso 3 para habilitar la autenticaci�n