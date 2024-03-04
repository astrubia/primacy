v0.0.1

# Primacy app
Primacy App es una aplicación de software diseñada para optimizar y automatizar los procesos de seguimiento y control de pacientes con patologías crónicas, ofreciendo una solución eficiente y amigable para mejorar la gestión de la atención en salud.

Descripción Funcional:

Portada
La portada ofrece una bienvenida visualmente atractiva, seguida del logo de la empresa, y mas abajo se encuentra:

* campos de inicio de sesión, donde el paciente puede ingresar con su usuario y contraseña, de manera segura y cifrada.
* Funcionalidad para restablecer la contraseña en caso de olvido, con un proceso seguro de verificación de identidad.
* Enlace para nuevos usuarios que deseen registrarse.
* Al pie de pantalla se encuentran los enlaces para las redes sociales de la empresa(facebook, instagram, linkedin).

Inicio de Sesión
La sección principal después del inicio de sesión en la App está diseñada para ofrecer una visión completa y accesible de las funcionalidades clave de la aplicación. Esta sección actúa como el hub central desde el cual los usuarios pueden realizar diversas acciones relacionadas con el seguimiento y cuidado de su salud.

* Constituida por una seccion de imagen de perfil de usuario arriba a la izquierda y el nombre de usuario arriba a la derecha.
* por debajo se encuentra el Menú constituido por botones visuales que facilitan la navegación hacia las diferentes secciones de la aplicación:
      _ informacion personal
      _ requerimientos
      _ historial de salud.
      _ controles
      _ consejeria
      _ afiliacion

Cada una de estos botones redirije a la seccion correspondiente.

1. Registro detallado de información personal
Comprende un formulario donde la persona carga por unica vez todos los datos necesarios para su registracion.
nombre, apellido, dni, numero de telefono, correo electronico, cuil, obra social, tipo de plan de obra social, numero de afiliado.
Una vez cargado los datos, esta seccion solo cumplira la funcion de mostrarlos.

2. Requerimientos
Destinada a la practicidad y comodidad del paciente para solicitar lo que necesite.
Cuenta con una serie de botones que cumplen la funcionalidad de generar un alerta, un aviso al personal administrativo de la empresa quienes se comunicaran inmediatamente con la persona para indigar sobre el requerimiento y darle la solucion que espera.
Los botones comprende la solicitud de: control, consulta, recetas, estudios complementarios, otros.
El boton de recetas podria estar acompañado de un campo donde el paciente pueda escribir que medicamento necesita o la posibilidad de subir una foto del mismo.

3. Datos de salud
Seccion que cuenta con un formulario donde la persona ingresa su patologias previas, tratamientos, alergias, factores de riesgo por unica vez al registrarse.
Una vez cargados los datos, estos solo se mostraran.
Tambien contara con un boton donde pueda ver y dercargar en pdf un resumen de historia clinica generado por su medico de cabecera.
Por ultimo contara con otro boton donde tendra la posibilidad de subir un pdf o jpg de resultados de estudios de imagenes, laboratorio o epicrisis de atenciones realizadas en otra institucion de salud, para adosar a su historial medico.

4. Controles (Seguimiento Remoto)
Es la seccion mas importante de todas y la que representa la esencia del modelo de negocio de la empresa.
Comprende formularios con input para Monitoreo continuo de signos vitales y parámetros de salud a través de autocontrol diario.
Estos campos estaran programados para que en caso de que los valores ingresados por el paciente, presenten alteraciones significativa, se genere un mensaje con indicaciones y recomendaciones al paciente y un alerta automática para el medico tratante, que le avise de los cambios en la condición del paciente.
En un principio se basara en 4 parametros vitales:
      _ presion arterial 
      _ glucemia 
      _ frecuencia cardiaca
      _ saturacion de oxigeno

Debajo de cada uno de los parametros controlados va una grafica que muestra la evolucion de los registros en el tiempo, y permite visualizar mejor la informacion y hacer estadisticas.

5. Educacion en salud y consejeria
Recursos educativos integrados para pacientes sobre sus condiciones médicas.
Sesiones de consejería virtual para proporcionar información alimentaria, de ejercicios fisicos y apoyo emocional.
Alertas de recordatorio para garantizar la adherencia al tratamiento.
Incorporacion de chatbot con inteligencia artificial (un modelo que use la api de chatgpt en la que se la haga fine-tuning especifico) para especializarlo en respuestas de salud.

6. Afiliación Online y Pago Electrónico
Proceso de afiliación en línea para nuevos pacientes.
Posibilidad de descargar el contrato digital, un checkbox para aceptar los terminos y condiciones, y un sistema de pago electrónico (pasarela de pago de mercado pago) para facilitar transacciones on-line.

## License

[MIT](https://choosealicense.com/licenses/mit/)


## Tech Stack

**Client:** Vue.js, TailwindCSS

**Server:** Python, Fastapi


## Installation

Install my-project with npm

```bash
  npm install my-project
  cd my-project
```
    
## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`API_KEY`

`ANOTHER_API_KEY`


## Appendix

Any additional information goes here


## API Reference

#### Get all items

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.


## Authors

- [@outit](https://gitlab.outit.ar/outit/primacy-salud/documentation/design)


## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.


## Acknowledgements

 
