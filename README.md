# Laboratorio_Neurocognicion_Social
Página de inicio de laboratorio de neurocognición social, Facultad de Psicología, UNAM

La página tendrá información sobre los temas de investigación e interés del laboratorio de neurocognición social, bibliografías referente a estos temas. Descripción de los integrantes del laboratorio y de los colaboradores externos. También se presentará información de los proyectos que se esten realizando en ese momento y los investigadores involucrados. Así como las maneras en participar como colaborador o como participante en los proyectos de investigación. Enlaces de interés, eventos de interés, publicaciones de interés.


# Uso de Jekyll local para desarrollo

En la carpeta **docs** se crea un sitio para mostrar las presentaciones y pequeños resumenes.

Para mostrar localmente el sitio, se necesita instalar `ruby`, `bundler` y `rake`.

- `ruby`: Es el lenguaje en el cual corre el servidor **jekyll**
- `bundler`: Permite gestionar las dependencias de las diferentes gemas que necesitamos.
- `rake`: Permite gestionar y automatizar tareas

Para instalar bundler:

```
gem install bundler
```

Para instalar las dependencias, necesitamos un archivo **Gemfile** que contenga las gemas que vamos a instalar y en el
directorio se ejecuta:

```
bundle install
```

Ademas necesitamos un **Rakefile** donde se describa los parametros que ejecuta la tarea.
Para correr el servidor localmente en [http://localhost:4000](http://localhost:4000) ejecutamos:

```
bundle exec rake servidor
```
