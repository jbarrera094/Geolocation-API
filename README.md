# IP Geolocation Threat

Este proyecto es una simple aplicación web que permite a los usuarios obtener información de geolocalización de una dirección IP. Utiliza la API pública de [freeipapi.com](https://freeipapi.com/) para recuperar los datos de geolocalización en formato JSON y mostrarlos en la página web.

## Características

- Permite a los usuarios ingresar una dirección IP en un formulario.
- Recupera la información de geolocalización asociada a la IP usando la API de freeipapi.com.
- Muestra los resultados en la página en formato JSON.
- Utiliza la librería [Pico CSS](https://picocss.com/) para el estilo básico de la página.

## Requisitos Previos

Para ejecutar este proyecto, no se requieren dependencias adicionales, ya que todo el código necesario está incluido en el archivo `index.html`.

## Uso

1. Clona o descarga este repositorio en tu máquina local.
2. Abre el archivo `index.html` en tu navegador web.
3. Ingresa una dirección IP en el campo de texto proporcionado.
4. Haz clic en el botón "Submit".
5. La información de geolocalización se mostrará en la página en formato JSON.

## Estructura del Proyecto

```plaintext
.
├── index.html  # Archivo principal de la aplicación
└── README.md   # Documentación del proyecto
```

## Persoanlización
Puedes modificar el archivo index.html para adaptarlo a tus necesidades, como cambiar el estilo, agregar validaciones adicionales o integrar con otra API.

## Notas
- Asegúrate de no abusar de la API gratuita de freeipapi.com para evitar ser bloqueado.
- Este proyecto es una demostración básica, por lo que no incluye características avanzadas como manejo de errores robusto o soporte para múltiples idiomas.

## Licencia
Este proyecto está bajo la Licencia MIT. Puedes ver más detalles en el archivo LICENSE que debería acompañar este proyecto.