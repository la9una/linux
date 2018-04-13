En ocasiones, resulta práctico disponer de un atajo frente a largos y repetitivos comandos. Para eso sirven los _alias_. 

## Creando el alias
Simplemente, _logueados_ con nuestro usuario y estando en nuestra _home_, tendremos que abrir el archivo oculto `.bashrc`:

```bash
vim .bashrc

```

Una vez allí nos dirigimos al final del archivo (es indistinto) y agregamos la línea del alias a crear, que tendrá la siguiente sintaxis: 

```bash
alias nombreCorto='Comandos a ejecutar'
```

Por ejemplo (de más está decir lo peligroso del comando): 

```bash
alias borrar='cd && rm -rf *'
```

Luego, guardamos y salimos del editor. 

Finalmente, para que se apliquen los cambios, ejecutamos: 

```bash
. .bashrc
```

Listo! A partir de ahora, en lugar de ejecutar un comando completo, simplemente ejecutaremos en la terminal el nombre corto que elegimos asociado a la acción que configuramos en el _alias_. 