# 🎓 Taller Práctico: Dominando la Factura Electrónica

## Ejercicio 1: Configuración y Simulación de Emisor
Objetivo: Familiarizarse con el entorno y la carga de datos propios.

* Tarea: Entrar en la versión online de [MiFacturae](https://mifacturae.face.gob.es/) y completar el perfil de "Mis Datos".
* Reto: Configurar un IBAN de prueba y añadir un logo (si el software lo permite) o una descripción comercial por defecto.
* Resultado esperado: El alumno debe mostrar el panel de configuración con sus datos de "autónomo" o "empresa" correctamente guardados.

## Ejercicio 2: La Caza del DIR3 🕵️‍♂️
Objetivo: Aprender a localizar la identidad administrativa de un cliente.

* Tarea: Imagina que has realizado un servicio de mantenimiento para el Ayuntamiento de Madrid.
* Reto: Utiliza el Buscador de Unidades DIR3 de FACe para encontrar los tres códigos (Oficina Contable, Órgano Gestor y Unidad Tramitadora) del área de "Cultura, Turismo y Deporte".
* Resultado esperado: El alumno debe anotar los tres códigos correctos (ej. L01280796...).

## Ejercicio 3: Generación de Factura Profesional con IRPF
Objetivo: Crear un archivo real (pero no enviarlo) con retenciones.

* Tarea: Crear una factura para el cliente del ejercicio anterior por un importe de 1.000€ (base imponible).
* Condiciones:
* Añadir IVA al 21%.
   * Añadir una retención de IRPF del 15% (típica de autónomos).
   * Incluir en el concepto: "Talleres de formación en digitalización - Mayo 2024".
* Resultado esperado: Descargar el archivo .xsig y comprobar que el total de la factura es correcto (1.000 + 210 - 150 = 1.060€).

## Ejercicio 4: Validación y "Casi" Envío
Objetivo: Aprender a usar las herramientas de verificación.

* Tarea: Coger el archivo .xsig generado en el ejercicio anterior y pasarle un control de calidad.
* Reto: Subirlo al Portal de Validación de FACe para comprobar si el formato es correcto y si la firma es válida.
* Resultado esperado: Obtener el "Check verde" de validación de firma y formato.

