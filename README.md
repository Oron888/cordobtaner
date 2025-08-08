Aquí tienes un ejemplo de README para GitHub, explicando el propósito, instalación y funcionamiento del código:

---

# Buscador de Coordenadas DMS

Este proyecto es una aplicación de escritorio creada con Python y Tkinter para buscar coordenadas geográficas en formato **DMS** (grados, minutos, segundos) o **decimal**. Utiliza la API de OpenCage para obtener las coordenadas de una ubicación especificada, como país, estado/provincia, ciudad y dirección. Además, el programa permite ver un mapa interactivo con la ubicación seleccionada.

### Características

* **Interfaz Gráfica de Usuario (GUI)**: La aplicación permite interactuar con menús desplegables para seleccionar país, provincia/estado, ciudad y calle para obtener coordenadas.
* **Soporte para coordenadas en DMS y decimal**: El usuario puede elegir el formato en el que desea ver las coordenadas.
* **Mapas interactivos**: Se utiliza la librería `tkintermapview` para mostrar un mapa interactivo y ubicar la posición seleccionada.
* **API de OpenCage**: Se hace uso de la API de OpenCage para obtener las coordenadas cuando no se encuentran en los datos locales.
* **Easter Egg**: Un logo interactivo que muestra a "Steve" al hacer clic sobre él.
* **Tema Claro**: Actualmente, el único tema disponible es el claro (con una opción para configurar el estilo visual).

### Tecnologías utilizadas

* **Python**: Lenguaje de programación utilizado para desarrollar la aplicación.
* **Tkinter**: Librería de interfaz gráfica de usuario (GUI) para Python.
* **pygame**: Para la reproducción de efectos de sonido.
* **pycountry**: Para obtener información sobre países y divisiones administrativas.
* **tkintermapview**: Librería para integrar mapas interactivos en Tkinter.
* **OpenCage API**: Servicio para obtener coordenadas geográficas de una dirección.

### Uso

1. Ejecuta el archivo `APP.EXE` para iniciar la aplicación

2. En la interfaz de la aplicación, selecciona un país, una provincia/estado y una ciudad. Si lo deseas, puedes ingresar una calle y número para obtener coordenadas más precisas.

3. El resultado de las coordenadas aparecerá en formato DMS o decimal, dependiendo de la opción que elijas.

4. Puedes copiar las coordenadas al portapapeles y visualizar la ubicación en el mapa interactivo.

5. Al hacer clic en el logo de la aplicación, aparecerá un "Easter Egg" en forma de una imagen de "Steve", acompañado de un sonido de clic.

### Configuración

El código permite la selección del tema **claro**, y puedes ajustar la visualización de coordenadas en formato **DMS** o **decimal** en el menú de configuración.

### Contribuciones

Las contribuciones son bienvenidas. Si tienes una sugerencia o encuentras un error, por favor abre un "issue" o realiza un "pull request". Asegúrate de seguir el estilo de codificación y agregar pruebas si es necesario.

### Licencia

Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.

---

Este README proporciona una descripción clara sobre el propósito del proyecto, cómo instalarlo, utilizarlo y los requisitos. Asegúrate de modificar cualquier sección, como el nombre del repositorio, la API Key, etc., antes de subirlo a GitHub.
