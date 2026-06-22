# Requerimientos Funcionales  
## Sistema de Escritorio para la Gestión de Servicios Mecánicos Automotrices

| No. | Módulo | Requerimiento funcional |
|---:|---|---|
| 1 | Inicio de sesión | El sistema deberá permitir el inicio de sesión mediante usuario y contraseña para controlar el acceso al sistema. |
| 2 | Usuarios | El sistema deberá permitir registrar nuevos usuarios del taller, como administrador, recepcionista, mecánico o gerente. |
| 3 | Usuarios | El sistema deberá permitir asignar roles a los usuarios para limitar o habilitar funciones según sus responsabilidades. |
| 4 | Usuarios | El sistema deberá permitir modificar los datos de los usuarios registrados, como nombre, correo, teléfono y rol. |
| 5 | Usuarios | El sistema deberá permitir activar o desactivar usuarios sin eliminar permanentemente su información. |
| 6 | Clientes | El sistema deberá permitir registrar clientes con datos como nombre, teléfono, correo electrónico, dirección y observaciones. |
| 7 | Clientes | El sistema deberá permitir consultar el historial de servicios asociados a cada cliente. |
| 8 | Clientes | El sistema deberá permitir buscar clientes por nombre, teléfono, correo o número de identificación interna. |
| 9 | Clientes | El sistema deberá permitir actualizar la información de contacto de los clientes registrados. |
| 10 | Clientes | El sistema deberá permitir eliminar o marcar como inactivo a un cliente cuando ya no sea atendido por el taller. |
| 11 | Vehículos | El sistema deberá permitir registrar vehículos asociados a un cliente, incluyendo marca, modelo, año, color, placas, número de serie y kilometraje. |
| 12 | Vehículos | El sistema deberá permitir que un cliente tenga uno o varios vehículos registrados. |
| 13 | Vehículos | El sistema deberá permitir consultar el historial de reparaciones y mantenimientos realizados a cada vehículo. |
| 14 | Vehículos | El sistema deberá permitir actualizar los datos del vehículo, incluyendo kilometraje actual, placas o propietario. |
| 15 | Vehículos | El sistema deberá permitir buscar vehículos por placas, número de serie, marca, modelo o nombre del cliente. |
| 16 | Citas | El sistema deberá permitir registrar citas para revisión, diagnóstico, mantenimiento o reparación de vehículos. |
| 17 | Citas | El sistema deberá permitir seleccionar fecha, hora, cliente, vehículo y tipo de servicio al crear una cita. |
| 18 | Citas | El sistema deberá mostrar la agenda diaria, semanal o mensual de citas programadas. |
| 19 | Citas | El sistema deberá permitir modificar la fecha u hora de una cita previamente registrada. |
| 20 | Citas | El sistema deberá permitir cancelar citas, registrando el motivo de la cancelación. |
| 21 | Recepción de vehículo | El sistema deberá permitir registrar la entrada de un vehículo al taller. |
| 22 | Recepción de vehículo | El sistema deberá permitir capturar el kilometraje, nivel de combustible, estado general y observaciones al recibir el vehículo. |
| 23 | Recepción de vehículo | El sistema deberá permitir registrar accesorios o pertenencias que el cliente deja dentro del vehículo. |
| 24 | Recepción de vehículo | El sistema deberá permitir generar una orden de servicio al momento de recibir el vehículo. |
| 25 | Orden de servicio | El sistema deberá permitir crear órdenes de servicio asociadas a un cliente, vehículo y mecánico responsable. |
| 26 | Orden de servicio | El sistema deberá permitir registrar la descripción del problema reportado por el cliente. |
| 27 | Orden de servicio | El sistema deberá permitir clasificar el tipo de servicio, como mantenimiento preventivo, mantenimiento correctivo, diagnóstico, reparación eléctrica, suspensión, frenos, motor o transmisión. |
| 28 | Orden de servicio | El sistema deberá permitir asignar una prioridad a la orden de servicio, como baja, media, alta o urgente. |
| 29 | Orden de servicio | El sistema deberá permitir cambiar el estado de la orden de servicio, por ejemplo: recibida, en diagnóstico, en reparación, pendiente de refacciones, finalizada o entregada. |
| 30 | Diagnóstico | El sistema deberá permitir registrar el diagnóstico técnico realizado por el mecánico. |
| 31 | Diagnóstico | El sistema deberá permitir agregar fallas detectadas, causas probables y recomendaciones técnicas. |
| 32 | Diagnóstico | El sistema deberá permitir adjuntar evidencias del diagnóstico, como fotografías, notas o documentos. |
| 33 | Cotización | El sistema deberá permitir generar cotizaciones a partir del diagnóstico registrado. |
| 34 | Cotización | El sistema deberá permitir agregar mano de obra, refacciones, insumos y servicios externos a una cotización. |
| 35 | Cotización | El sistema deberá calcular automáticamente el subtotal, impuestos, descuentos y total de la cotización. |
| 36 | Cotización | El sistema deberá permitir aprobar, rechazar o modificar una cotización antes de iniciar la reparación. |
| 37 | Reparación | El sistema deberá permitir registrar las actividades realizadas durante la reparación del vehículo. |
| 38 | Reparación | El sistema deberá permitir asignar uno o varios mecánicos a una misma orden de servicio. |
| 39 | Reparación | El sistema deberá permitir registrar avances de la reparación con fecha, hora, responsable y descripción del trabajo realizado. |
| 40 | Reparación | El sistema deberá permitir marcar tareas como pendientes, en proceso o terminadas dentro de una orden de servicio. |
| 41 | Inventario | El sistema deberá permitir registrar refacciones, herramientas e insumos disponibles en el taller. |
| 42 | Inventario | El sistema deberá permitir controlar entradas y salidas de refacciones utilizadas en las órdenes de servicio. |
| 43 | Inventario | El sistema deberá descontar automáticamente del inventario las refacciones utilizadas en una reparación. |
| 44 | Inventario | El sistema deberá alertar cuando una refacción o insumo tenga existencia mínima o se encuentre agotado. |
| 45 | Proveedores | El sistema deberá permitir registrar proveedores de refacciones, herramientas, aceites, lubricantes y otros insumos. |
| 46 | Proveedores | El sistema deberá permitir consultar compras realizadas a cada proveedor. |
| 47 | Pagos | El sistema deberá permitir registrar pagos realizados por los clientes, indicando monto, fecha, método de pago y concepto. |
| 48 | Pagos | El sistema deberá permitir registrar pagos parciales, anticipos y liquidaciones de una orden de servicio. |
| 49 | Reportes | El sistema deberá generar reportes de servicios realizados por periodo, cliente, vehículo, mecánico o tipo de servicio. |
| 50 | Entrega de vehículo | El sistema deberá permitir registrar la entrega del vehículo al cliente, incluyendo fecha, hora, responsable, monto pagado y observaciones finales. |



## Tabla de Colaboradores para Revisión y Aprobación de Cambios

| Nombre                        | Usuario             | Puesto | Estatus Validación| Comentarios|
|-------------------------------|---------------------|--------|---|---|
| M.T.I. Marco A. Ramírez   | [MTI-MarcoRH](https://github.com/MTI-MarcoRH)        | Líder de Proyecto       |🟢 Aprobados |Sin observaciones|
| Jesús Yahir Calderón López        | [250802-eng](https://github.com/250802-eng)       |   Administrador de Bases de Datos     |🔴 No Aprobados  |Sin observaciones|
| Carlos Eduardo Antonio Alvarez    | [charles-antt](https://github.com/charles-antt)             |  Líder de Desarrollo      |🔴 No Aprobados  |Sin observaciones|
| Bertha Hernández Aranda        | [251113-BerthaHernandezAranda](https://github.com/251113-BerthaHernandezAranda)            | Ingeniero de Calidad       |🔴 No Aprobados  |Sin observaciones|
| Jeovani Cantellano Vargas        | [Jeovany-Vargas](https://github.com/Jeovany-Vargas)            | Cliente     |🟢  Aprobados  |Sin observaciones|




