# Miniblog-Flask-Pyton-SQLAlchemy
# Funcionalidades de este miniblog
* Existiran 2 tipos de usuarios: administradores e invitados
* Un ususario administrador puede añadir, modificar y eliminar entradas del blog
* los usuarios invitados  pueden registrarse en el blog para comentar las diferentes entradas.
Un usuario administrador puede listar y eliminar usuarios, ademas de poder asisgnarles el rol de administrador.


### Variables de entorno
Para que el miniblog funcione debes crear las siguientes variables de entorno:

## Linux/Mac
  export Flask_APP="entrypoint"
  export Flask_Env="develoment"
  export APP_SETTINGS_MODULE="config.local"
  
## Windows

  set "Flask_APP=entrypoint"
  set "Flask_ENV=develoment"
  set "APP_SETTINGS_MODULE=config.local"
  
  
 Añadir variables en el fichero "activate" o "activate.bat"
 si estas usando virtualenv
 
 
## Instalacion de dependencias
basta con ejecutar el fichero (requirements.txt) con todas las dependencias. para instalarlas basta con ejecutar
  pip install -r requirements.txt
  
## Ejecucion 
Una vez que hayas descargado el proyecto, creado las variables de entorno e instalado las dependencias, puedes arrancar el proyecto ejecutando:

    flask run
    
    
    
  
