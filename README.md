# Landing Page con Formulario

Esta es una landing page simple con un formulario de contacto.

## Características

- Diseño minimalista y atractivo.
- Formulario de contacto para que los visitantes puedan enviar mensajes.
- Validación de campos para asegurar que se ingresen datos válidos.
- Integración con una base de datos para almacenar los mensajes recibidos.

## Tecnologías utilizadas

- HTML5 y CSS3 para la estructura y el diseño de la página.
- JavaScript para la validación del formulario y la interacción con la base de datos.
- MySQL para almacenar los mensajes recibidos.

## Instalación

1. Clona este repositorio en tu máquina local.
2. Abre el archivo `index.html` en tu navegador web.

## Uso

1. Completa los campos del formulario con tus datos.
2. Haz clic en el botón "Enviar" para enviar el mensaje.
3. El mensaje será almacenado en la base de datos y recibirás una confirmación.

## Contribución

Si deseas contribuir a este proyecto, sigue estos pasos:

1. Haz un fork de este repositorio.
2. Crea una rama con el nombre de tu nueva funcionalidad (`git checkout -b nueva-funcionalidad`).
3. Realiza los cambios necesarios y haz commit (`git commit -m "Agrega nueva funcionalidad"`).
4. Haz push a la rama (`git push origin nueva-funcionalidad`).
5. Abre un pull request en este repositorio.

## Licencia

Este proyecto está bajo la Licencia MIT. Puedes ver el archivo [LICENSE](LICENSE) para más detalles.

# COMENTARIOS DE TIBOR - Descripcion del proceso de creacion y colocacion de iconos
1. Hemos accedido a cada elemento input cuales queremos que tengan un icono con pseudoelemento :nth-child(n) 
2. Los iconos estan en la carpeta 'svg' en forma de imagen SVG. Los iconos se visualizan como el fondo de la caja o elemento input, con css propiedad background.
3. Se ha utilizado el mismo color que tiene el elemento padre input - blanco #fff, luego llamamos la URL relativa de la imagen SVG, por ejemplo "../img/business.svg" accediendo al icono. Le ponemos que no se repita, lo colocamos con el tamano 8px del borde izquierda y lo centramos con 'center'. Ademas de esto, le ponemos el padding de arriba/abajo de 0, y de izquierda y derecha 40px.
4. Observamos nuestro trabajo y seamos felices.
