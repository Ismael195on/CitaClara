# CitaClara

Una app Android para encontrar peluquerías y barberías, reservar cita y ver cortes, y para que los negocios gestionen su agenda desde el móvil.

Es mi proyecto intermodular de 2º DAM en el CIFP Virgen de Gracia (Puertollano). *CitaClara es un nombre provisional.*

## Por qué la hago

Hablé con una peluquera autónoma de Puertollano y me contó que lleva las citas entre una agenda de papel, WhatsApp y llamadas. Pierde cerca de una hora al día en eso, y cada cancelación de última hora le deja un hueco que vale unos 40-50 €. Ya había probado una app que dejó a las dos semanas por ser difícil de usar. Quiero hacer una más sencilla, pensada para negocios pequeños como el suyo.

## Qué voy a hacer

**Para el cliente**
- Buscar peluquerías y barberías en lista o en un mapa.
- Ver la ficha del negocio, reservar cita y cancelarla.
- Ver una galería de cortes y guardar los que me gusten.
- Tener un perfil con mis peluquerías visitadas y mis favoritos.

**Para el negocio**
- Afiliarse a la app y aparecer en el mapa.
- Gestionar servicios, profesionales y horarios.
- Llevar la agenda de citas sin que se solapen.

Con las ideas que he sacado de analizar Booksy, también quiero meter recordatorios de cita y una política de cancelación.

## Tecnologías

| | |
|---|---|
| App | Kotlin, Android Studio, Jetpack Compose, MVVM, Ktor Client |
| Mapa | Maps SDK para Android |
| Servidor | API REST en PHP con Apache (XAMPP) |
| Base de datos | MySQL (phpMyAdmin) |
| Otras | Git y GitHub, Figma, draw.io |

La app no habla directamente con la base de datos: todo pasa por la API en PHP.

## Cómo va el proyecto

- [x] Mapa de frustraciones y entrevista a una peluquera
- [x] Propuesta de proyecto
- [x] Primera entrega (situación actual, objetivos y análisis de Booksy)
- [ ] Proyecto Android creado en este repositorio
- [ ] Base de datos MySQL con las primeras tablas
- [ ] API en PHP: registro e inicio de sesión
- [ ] Pantalla de login en Compose

## Lo siguiente

1. Crear el proyecto Android y subir el primer commit.
2. Montar la base de datos en XAMPP con las tablas `usuario` y `negocio`.
3. Hacer el registro y el login de principio a fin, de la pantalla a la base de datos.

## Documentación

Todo el detalle (problema, objetivos, base de datos, seguridad, competencia) está en la carpeta [`docs/`](docs/):

- [Propuesta de proyecto](docs/Propuesta_Proyecto_CitaClara_Ismael_Munoz.pdf)
- [Primera entrega](docs/Primera_Entrega_CitaClara_Ismael_Munoz.pdf)

## Autor

Ismael Muñoz Vico · 2º DAM · Tutora: Alicia Velasco Fernandez
