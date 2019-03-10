# Laboratorio Neurocognicion Social
Página de inicio de laboratorio de neurocognición social, Facultad de Psicología, UNAM

La página tendrá información sobre los temas de investigación e interés del laboratorio de neurocognición social, bibliografías referente a estos temas. Descripción de los integrantes del laboratorio y de los colaboradores externos. También se presentará información de los proyectos que se esten realizando en ese momento y los investigadores involucrados. Así como las maneras en participar como colaborador o como participante en los proyectos de investigación. Enlaces de interés, eventos de interés, publicaciones de interés.

Se puede acceder al sitio desde [https://neurocogcialab.org/](https://neurocogcialab.org/)


# Uso de Jekyll local para desarrollo

En la carpeta **docs** se crea un sitio para mostrar las presentaciones y pequeños resumenes.

Para mostrar localmente el sitio, se necesita instalar `ruby`, `bundler` y `rake`.

- `ruby`: Es el lenguaje en el cual corre el servidor **jekyll**
- `bundler`: Permite gestionar las dependencias de las diferentes gemas que necesitamos.
- `rake`: Permite gestionar y automatizar tareas

La instalación de **ruby** sale del obejtivo de este README y dependen del sistema operativo que se utilice.

Con **ruby** instalado, podemos instalar bundler:

```
gem install bundler
```

> Bundler se instala a nivel máquina, así que al igual que **ruby** solo se hace en una ocasión. Si el comando 
> falla probablemente debamos revisar nuestra instalación de **ruby**.

**Bundler** permite instalar *gemas* considerando sus dependencias. Para esto necesitamos un archivo **Gemfile** que contenga 
las gemas que vamos a instalar y en el directorio se ejecuta, este archivo ya esta generado en la carpeta **docs**, por lo 
tanto basta ejecutar dentro de esa carpeta:

```
bundle install
```

> Este proceso solo se debe ejecutar una vez por maquina. Si esto falla, probablemente tengas un problema con la instalación de bundler.


Dentro de las dependencias que definimos esta **rake** que permite ejecutar **acciones** específicas y nos facilita la
puesta en marcha de nuestro servidor local jekyll. 
Para correr el servidor localmente en [http://localhost:4000](http://localhost:4000) ejecutamos:

```
bundle exec rake servidor
```

> Este comado se ejecuta cada vez que queramos visualizar como se verá nuestra pagina localmente y en esa dirección
> podemos entrar y ver nuestros cambios previo a la subirlos al repositorio. 
