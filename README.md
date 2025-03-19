# Rocketbot 🚀: Entrega final - BotSolutions

![RPA file gathering](https://github.com/user-attachments/assets/4e349183-8e01-4355-b3a5-cd36a9a20618)

## Índice 📋

1. Descripción del proyecto.
2. Acceso al proyecto.
3. Demostración del funcionalidades y aplicaciones.
4. Tecnologías utilizadas.
5. Colaboradores.
6. Desarrollador del proyecto.

## 1. Descripción del proyecto 📚

Este proyecto RPA esta destinado a la recolección y organización de los proyectos realizados a lo largo de la primera capacitación en dicha tecnología. Su finalidad es presentar deforma unificada todos los proyectos junto con el Curriculum Vitae del desarrollador de los mismos, y enviar dicho conjunto en un solo archivo a las personas interesadas.

## 2. Acceso al proyecto 📂

Para obtener el proyecto tienes dos opciones:

1. Clonar el repositorio utilizando la línea de comandos. Solo debes dirigirte al directorio donde deseas clonar el mismo e ingresar el comando:
   `https://github.com/ignaciomajo/botsolutions_trabajo_final/`

2. O puedes descargarlo directamente desde el repositorio en GitHub en el siguiente enlace:
   <p><a href="https://github.com/ignaciomajo/botsolutions_trabajo_final/">https://github.com/ignaciomajo/botsolutions_trabajo_final/</p>

   Esto te llevará a la siguiente pantalla, donde deberás seguir los siguientes pasos:
   
![archivo_zip](https://github.com/user-attachments/assets/f93395f8-fffc-494a-8bc6-206b29bd2d50)


Esto descargará un archivo comprimido `.zip`, que podras alojar en el directorio que desees.

## 3. Demostración de funcionalidades y aplicaciones 📝

![upload_db](https://github.com/user-attachments/assets/4073d788-ef25-4033-b118-5f6854aad413)

Al cargar el archivo `robot.db` 📄, la base de datos aparecerá a la derecha del panel. Al hacer click en esta, nos aparecerá el siguiente menú:

![menu_db](https://github.com/user-attachments/assets/af804a10-eed9-48ed-b529-2c71ad0b9e25)

En él, se pueden visualizar los robots alojados dentro de la base de datos, en este caso, contiene uno solo.

![pantalla_inicial](https://github.com/user-attachments/assets/5482854a-601b-45be-bdb2-20483d64cf84)

Esta será la pantalla inicial.

* En la parte superior de la pantalla, podemos ver encerrado en un recuadro rojo el botón de **Run**, que ejecutará todo el proceso completo.
* El recuadro azul, muestra la asignación a una variable de la fecha y hora en tiempo real de la inicialización del proceso para un registro de logs customizado.
* Por ultimo, el recuadro verde corresponde a las configuraciones iniciales tomadas del archivo `config.ini`📄 que contiene todos los paths necesarios para la búsqueda y recolección de los proyectos y curriculum, como también el directorio donde serán organizados.

![copia_proyectos](https://github.com/user-attachments/assets/7c60479e-2774-4894-8b44-75fe956ad251)

Una vez realizadas las configuraciones iniciales, el robot tomará los paths obtenidos del archivo `config.ini`📄 y recopilará los proyectos en cuestión, junto con el CV del desarrollador, para organizarlos en un solo directorio📁.

![eliminacion_bat](https://github.com/user-attachments/assets/f280a333-0aa7-4f1a-b388-ce1536225a1e)

Este paso se encarga de eliminar los archivos `main.bat`💾, ya que Gmail bloquea los archivos con dicha extensión. 

*Nota: `main.bat`💾 es el archivo que se utiliza para poner el robot en producción. Debido a que este proyecto es solo para presentación de desarrollos, dicho archivo no será necesario. En caso de que el proyecto sea con finalidades de producción, se debe buscar otro medio para compartir el robot.*

![compresion](https://github.com/user-attachments/assets/a72128f1-c011-40e6-a9a7-087d7a5a000c)

Se comprimen los proyectos y el Curriculum Vitae del desarrollador en un solo archivo para facilitar el envío y descarga a los destinatarios.

![gmail](https://github.com/user-attachments/assets/67450a06-7ace-4fd6-82c8-1c896950dc7d)

Aqui podemos ver la configuración del servidor de Gmail y su validación. En caso de que esta sea exitosa, se lleva a cabo el envío del correo con el archivo `proyectos.zip`📁 adjunto.


*Nota: Todas las validaciones tienen captura de error en caso de que algo ocurra, que quedarán registrados en el archivo `custom_logs.txt`📄 que se encuentra en la carpeta **resources**📁 dentro de **main**📁.*


## 4. Tecnologías utilizadas 🛠️

* `Rocketbot Studio (v.2025.01.06)`
* `Git and GitHub`
* `OBS (screen recorder)`
* `HTML`
* `Python`
* `Excel (requerido para ejecutar el robot)`

## 5. Colaboradores del proyecto 🏗️

Quiero agradecer a:

![BotSolutions](https://github.com/user-attachments/assets/4dda0262-5b97-4b60-a692-db5aa7825d4b)

#### BotSolutions

Por la capacitación en la herramienta y en la oportunidad de aprender de la mano de ellos.

------------------------------------------------------------------------------------------------------
![Rocketbot](https://github.com/user-attachments/assets/5e61e12c-8fe3-4505-8463-0cf648ecda96)

#### Rocketbot

Por desarrollar la herramienta y proveer cursos gratuitos para aprender a utilizarla.


## 6. Desarrollador del proyecto 👷

![imagen-readme](https://github.com/user-attachments/assets/133bc743-0424-4120-a7a6-7245d2f28f8c)

**| Ignacio Majo | Data Scientist Junior | Junior RPA Developer |**
