
# Primacy app
Primacy App es una aplicación de software diseñada para optimizar y automatizar los procesos de seguimiento y control de pacientes con patologías crónicas, ofreciendo una solución eficiente y amigable para mejorar la gestión de la atención en salud.

Características Principales
1. Gestión de Pacientes
Registro detallado de información personal y médica de cada paciente.
Seguimiento de historiales médicos, tratamientos y consultas.

2. Programación de Citas
Sistema de programación de citas médicas para pacientes.
Sistema de solicitud de recetas y estudios complementarios.

3. Seguimiento Remoto
Monitoreo continuo de signos vitales y parámetros de salud a través de autocontrol.
Alertas automáticas para cambios significativos en la condición del paciente.

4. Educacion en salud y consejeria
Recursos educativos integrados para pacientes sobre sus condiciones médicas.
Sesiones de consejería virtual para proporcionar información alimentaria, de ejercicios fisicos y apoyo emocional.
Alertas de recordatorio para garantizar la adherencia al tratamiento.

5. . Afiliación Online y Pago Electrónico
Proceso de afiliación en línea para nuevos pacientes.
Sistema de pago electrónico para facilitar transacciones relacionadas con servicios médicos.


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

 
