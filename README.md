## Despliegue de apps SpringBoot en Heroku

Crear archivo 'system.properties' en el proyecto con el contenido:

'''
java.runtime.version=17
'''

1. Crear cuenta en heroku.com y github.com
2. Tener configurado git en el ordenador
   1. 'git config -- global user.name "XXXXX"'
   2. 'git config --global user.email example@example.com'
3. Subir el proyecto a Github desde Intellij IDEA desde la opción: VCD Share project on github
4. Desde Heroku crear app y elegir método Github y buscar el repositorio subdirectory
5. Habilitar deploy automático y ejecutar Deploy