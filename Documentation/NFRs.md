# Requerimientos No Funcionales  
## Sistema Gestor de Talleres Mecánicos - MecaGest Desktop

<div align="center">

<img src="../images/Product_Logo.png" alt="Logo MecaGest Desktop" width="360">

</div>

---

## Información del documento

| Elemento | Descripción |
|---|---|
| Proyecto | Sistema Gestor de Talleres Mecánicos |
| Nombre del software | MecaGest Desktop |
| Empresa desarrolladora | Soft3CDev |
| Tipo de sistema | Aplicación de escritorio |
| Base de datos | Relacional |
| Documento | Requerimientos No Funcionales |
| Versión | 1.0 |
| Estado | En revisión |
| Fecha | Pendiente de actualización |

---

## Propósito del documento

El presente documento describe los **Requerimientos No Funcionales (RNF)** sugeridos para el sistema **MecaGest Desktop**, una aplicación de escritorio orientada a la gestión de operaciones de talleres mecánicos locales.

A diferencia de los requerimientos funcionales, que describen lo que el sistema debe hacer, los requerimientos no funcionales establecen las condiciones de calidad, rendimiento, seguridad, usabilidad, mantenimiento y operación que debe cumplir el software.

Este documento forma parte de las prácticas de desarrollo colaborativo mediante **Git y GitHub**, por lo que podrá ser revisado, modificado y aprobado mediante ramas, commits, pull requests y validación por parte de los colaboradores del proyecto.

---

## Alcance de los requerimientos no funcionales

Los requerimientos descritos en este documento están pensados para una primera versión académica del sistema, considerando que será un software de escritorio con conexión a una base de datos relacional.

El sistema estará orientado a usuarios administrativos de talleres mecánicos, por lo que debe ser claro, estable, fácil de usar y capaz de manejar información como clientes, vehículos, órdenes de servicio, inventario, pagos y reportes básicos.

---

## Consideraciones generales del sistema

MecaGest Desktop se desarrollará como una aplicación de escritorio que podrá ejecutarse en una computadora del taller mecánico.

El sistema deberá conectarse a una base de datos relacional, como MySQL, SQLite, PostgreSQL u otra tecnología definida por el equipo de desarrollo.

El nivel del proyecto será académico, por lo que los requerimientos no funcionales deben ser realistas, alcanzables y adecuados para estudiantes que están practicando análisis, diseño, desarrollo, documentación y control de versiones.

---

# Lista de Requerimientos No Funcionales

| ID | Categoría | Requerimiento No Funcional | Descripción | Prioridad |
|---|---|---|---|---|
| RNF-001 | Usabilidad | Interfaz clara y sencilla | El sistema deberá contar con una interfaz gráfica fácil de comprender para usuarios con conocimientos básicos de computación. | Alta |
| RNF-002 | Usabilidad | Navegación intuitiva | Los módulos principales deberán estar organizados de forma clara para que el usuario pueda acceder rápidamente a clientes, vehículos, órdenes de servicio, inventario, pagos y reportes. | Alta |
| RNF-003 | Rendimiento | Respuesta rápida en operaciones comunes | El sistema deberá responder de forma ágil al registrar, consultar, actualizar o eliminar información básica. | Alta |
| RNF-004 | Rendimiento | Consultas eficientes a la base de datos | Las consultas a la base de datos deberán estar diseñadas para evitar tiempos de espera innecesarios en búsquedas de clientes, vehículos, órdenes e inventario. | Media |
| RNF-005 | Seguridad | Acceso mediante usuario y contraseña | El sistema deberá contar con un mecanismo de inicio de sesión para restringir el acceso únicamente a usuarios registrados. | Alta |
| RNF-006 | Seguridad | Control básico de roles | El sistema deberá permitir diferenciar permisos de acuerdo con el tipo de usuario, por ejemplo administrador, recepcionista o mecánico. | Media |
| RNF-007 | Integridad de datos | Validación de información ingresada | El sistema deberá validar los datos capturados por el usuario para evitar registros incompletos, duplicados o con formatos incorrectos. | Alta |
| RNF-008 | Integridad de datos | Relación correcta entre entidades | El sistema deberá mantener la relación adecuada entre clientes, vehículos, órdenes de servicio, refacciones y pagos dentro de la base de datos relacional. | Alta |
| RNF-009 | Disponibilidad | Operación local del sistema | El sistema deberá poder ejecutarse en una computadora de escritorio o laptop del taller sin depender obligatoriamente de conexión a internet. | Alta |
| RNF-010 | Mantenibilidad | Código organizado por módulos | El código fuente deberá organizarse en carpetas y módulos que separen interfaz, lógica de negocio, modelos, controladores y acceso a datos. | Alta |
| RNF-011 | Mantenibilidad | Uso de nombres claros | Las variables, clases, métodos, archivos y carpetas deberán tener nombres claros, descriptivos y relacionados con su función dentro del sistema. | Media |
| RNF-012 | Compatibilidad | Funcionamiento en sistema operativo definido | El sistema deberá ejecutarse correctamente en el sistema operativo seleccionado por el equipo, preferentemente Windows por ser común en entornos de oficina y talleres. | Alta |
| RNF-013 | Respaldo | Posibilidad de respaldar la base de datos | El sistema o la documentación técnica deberán contemplar un procedimiento básico para realizar respaldos de la base de datos. | Media |
| RNF-014 | Recuperación | Manejo de errores comunes | El sistema deberá mostrar mensajes claros cuando ocurra un error, por ejemplo fallas de conexión a la base de datos, campos vacíos o registros no encontrados. | Alta |
| RNF-015 | Escalabilidad | Estructura preparada para nuevos módulos | El sistema deberá diseñarse de manera que en el futuro puedan agregarse nuevos módulos, como facturación, proveedores, citas o reportes avanzados. | Media |
| RNF-016 | Accesibilidad | Textos y botones legibles | La interfaz deberá utilizar tamaños de letra, botones y colores que faciliten la lectura y operación básica del sistema. | Media |
| RNF-017 | Trazabilidad | Registro básico de cambios importantes | El sistema deberá considerar la posibilidad de registrar acciones importantes, como creación de órdenes, actualización de pagos o modificación de inventario. | Baja |
| RNF-018 | Calidad documental | Documentación clara del sistema | El proyecto deberá contar con documentación organizada sobre instalación, uso, base de datos, pruebas y estructura técnica. | Alta |

---

# Descripción por categoría

## Usabilidad

La usabilidad es fundamental debido a que el sistema está dirigido a usuarios de talleres mecánicos que no necesariamente tienen experiencia avanzada en software administrativo.

El sistema debe ser visualmente claro, con menús ordenados, botones identificables y formularios fáciles de llenar.

Ejemplos de aplicación:

- Botones con nombres claros como `Guardar`, `Cancelar`, `Buscar` o `Actualizar`.
- Formularios separados por secciones.
- Mensajes de confirmación al guardar información.
- Menús principales visibles desde el panel inicial.

---

## Rendimiento

El sistema debe responder de manera adecuada en operaciones comunes como registrar clientes, consultar vehículos o generar órdenes de servicio.

Aunque se trate de un proyecto académico, es importante que las consultas a la base de datos se diseñen correctamente para evitar lentitud innecesaria.

Ejemplos de aplicación:

- Evitar consultas duplicadas.
- Usar claves primarias y foráneas.
- Filtrar información mediante búsquedas.
- No cargar datos innecesarios en pantalla.

---

## Seguridad

El sistema debe proteger el acceso a la información del taller mediante un inicio de sesión básico.

También se recomienda manejar roles para limitar ciertas acciones dependiendo del tipo de usuario.

Ejemplos de roles:

| Rol | Permisos sugeridos |
|---|---|
| Administrador | Acceso total al sistema |
| Recepcionista | Clientes, vehículos y órdenes de servicio |
| Mecánico | Consulta de órdenes asignadas |
| Cajero | Registro de pagos y consulta de adeudos |

---

## Integridad de datos

La información almacenada debe ser consistente y confiable.

El sistema debe evitar errores como registrar vehículos sin cliente, órdenes sin vehículo, pagos sin orden de servicio o refacciones con cantidades negativas.

Ejemplos de validaciones:

- No permitir campos obligatorios vacíos.
- Validar formato de teléfono.
- Validar que el costo sea mayor o igual a cero.
- Evitar placas duplicadas si el diseño de la base de datos lo requiere.
- Confirmar antes de eliminar registros importantes.

---

## Disponibilidad

Al ser un sistema de escritorio, se espera que pueda ser utilizado directamente desde una computadora del taller.

Para una primera versión, no será obligatorio depender de servicios en la nube o conexión constante a internet.

La disponibilidad dependerá principalmente de:

- Correcta instalación del sistema.
- Correcta conexión con la base de datos.
- Equipo de cómputo funcional.
- Procedimientos básicos de respaldo.

---

## Mantenibilidad

El sistema deberá desarrollarse de manera ordenada para facilitar futuras correcciones, mejoras o integración de nuevos módulos.

Se recomienda separar el código en capas o carpetas.

Estructura sugerida:

```txt
src/
├── controllers/
├── models/
├── views/
├── services/
├── repositories/
└── utils/
```

---

## Compatibilidad

El equipo deberá definir el sistema operativo principal sobre el cual se ejecutará el software.

Para fines académicos y por el contexto de uso en talleres mecánicos, se recomienda considerar inicialmente equipos con sistema operativo Windows.

La compatibilidad exacta dependerá del lenguaje y framework seleccionado para el desarrollo.

---

## Respaldo y recuperación

El sistema deberá contemplar la importancia de proteger la información del taller.

Aunque el respaldo puede implementarse en una etapa posterior, la documentación técnica deberá describir un procedimiento básico para respaldar la base de datos.

Ejemplos:

- Copia manual del archivo de base de datos.
- Exportación mediante script SQL.
- Carpeta de respaldos.
- Fecha y responsable del respaldo.

---

# Criterios generales de aceptación

Para considerar válidos estos requerimientos no funcionales, se deberán cumplir los siguientes criterios:

| Criterio | Descripción |
|---|---|
| Claridad | Cada RNF debe estar redactado de forma comprensible |
| Relación con el proyecto | Cada RNF debe responder al contexto de un taller mecánico |
| Viabilidad | Los RNF deben ser alcanzables para el nivel actual de desarrollo |
| Evidencia | Cada RNF deberá poder comprobarse mediante revisión, prueba o captura |
| Trazabilidad | Los RNF deberán relacionarse con módulos o documentos del proyecto |
| Aprobación | Los cambios deberán ser revisados mediante la tabla de colaboradores |

---

# Evidencias sugeridas para validar los RNF

| RNF | Evidencia sugerida |
|---|---|
| RNF-001 | Capturas de pantalla de la interfaz |
| RNF-003 | Pruebas de registro y consulta |
| RNF-005 | Captura del inicio de sesión |
| RNF-007 | Capturas de validaciones de formularios |
| RNF-008 | Diagrama relacional de base de datos |
| RNF-010 | Captura de estructura de carpetas |
| RNF-013 | Archivo o procedimiento de respaldo |
| RNF-014 | Capturas de mensajes de error |
| RNF-018 | Carpeta de documentación organizada |

---

# Relación con otros documentos

Los detalles técnicos y de análisis del sistema se documentarán en archivos independientes dentro del repositorio.

| Documento | Ubicación sugerida |
|---|---|
| Requerimientos funcionales | `docs/02-analisis/requerimientos-funcionales/README.md` |
| Requerimientos no funcionales | `docs/02-analisis/requerimientos-no-funcionales/README.md` |
| Reglas de negocio | `docs/02-analisis/reglas-negocio/README.md` |
| Base de datos | `docs/04-base-datos/README.md` |
| Casos de uso | `docs/03-diseno/casos-uso/README.md` |
| Manual técnico | `docs/07-manuales/manual-tecnico.md` |
| Manual de usuario | `docs/07-manuales/manual-usuario.md` |
| Pruebas | `docs/06-pruebas/README.md` |

---

# Uso dentro de la práctica de Git y GitHub

Este documento puede utilizarse como base para simular un flujo de desarrollo colaborativo.

## Actividades sugeridas

1. Crear una rama para trabajar los requerimientos no funcionales.

```bash
git checkout -b docs/requerimientos-no-funcionales
```

2. Agregar o modificar el archivo `README.md` de esta sección.

```bash
git add docs/02-analisis/requerimientos-no-funcionales/README.md
```

3. Realizar un commit descriptivo.

```bash
git commit -m "docs: agregar requerimientos no funcionales"
```

4. Enviar la rama al repositorio remoto.

```bash
git push origin docs/requerimientos-no-funcionales
```

5. Crear un Pull Request en GitHub.

6. Solicitar revisión a los colaboradores.

7. Actualizar la tabla de aprobación de cambios.

---

# Tabla de Colaboradores para Revisión y Aprobación de Cambios

| Nombre                        | Usuario             | Puesto | Estatus Validación| Comentarios|
|-------------------------------|---------------------|--------|---|---|
| M.T.I. Marco A. Ramírez   | [MTI-MarcoRH](https://github.com/MTI-MarcoRH)        | Líder de Proyecto       |🟢 Aprobados |Sin observaciones|
| Jesús Yahir Calderón López        | [250802-eng](https://github.com/250802-eng)       |   Administrador de Bases de Datos     |🔴 No Aprobados  |Sin observaciones|
| Carlos Eduardo Antonio Alvarez    | [charles-antt](https://github.com/charles-antt)             |  Líder de Desarrollo      |🔴 No Aprobados  |Sin observaciones|
| Bertha Hernández Aranda        | [251113-BerthaHernandezAranda](https://github.com/251113-BerthaHernandezAranda)            | Ingeniero de Calidad       |🔴 No Aprobados  |Sin observaciones|
| Jeovani Cantellano Vargas        | [Jeovany-Vargas](https://github.com/Jeovany-Vargas)            | Cliente     |🟢  Aprobados  |Sin observaciones|

---

# Historial de cambios del documento

| Versión | Fecha | Autor | Descripción |
|---|---|---|---|
| 1.0 | Pendiente | Soft3CDev | Creación inicial del documento de requerimientos no funcionales |

---

# Observaciones finales

Los requerimientos no funcionales definidos en este documento permitirán establecer criterios mínimos de calidad para el desarrollo de **MecaGest Desktop**.

Al tratarse de un sistema de escritorio con conexión a base de datos relacional, se recomienda priorizar la usabilidad, integridad de datos, seguridad básica, rendimiento en consultas comunes y organización del código fuente.

Este documento podrá actualizarse conforme avance el análisis, diseño, desarrollo y validación del sistema.
