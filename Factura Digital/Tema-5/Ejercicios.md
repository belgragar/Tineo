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

## 🎓 Ejercicio 5: Corrección de Errores (La Factura Rectificativa)
Contexto:
Imagina que tras enviar la factura del Ejercicio 3 (la de 1.060€ al Ayuntamiento de Madrid), recibes un aviso: "El importe es incorrecto porque olvidaste aplicar un descuento del 10% acordado por contrato".
Objetivo:
Aprender a anular la factura anterior y emitir la correcta siguiendo el protocolo legal de Facturae.
Instrucciones para el alumno:

   1. Preparación: Ten a mano el número de factura y la fecha de la factura que generaste en el Ejercicio 3.
   2. Nueva Factura: Inicia el proceso en MiFacturae, pero esta vez selecciona en el desplegable de "Tipo de Factura": Factura Rectificativa.
   3. Vínculo Legal:
   * Busca la sección "Detalle de Rectificación".
      * Introduce el número y la fecha de la factura del Ejercicio 3.
      * En "Código de Motivo", selecciona: 02 - Cálculo de importes.
   4. Cálculo del Nuevo Importe:
   * Aplica el descuento del 10% sobre la base imponible original (1.000€ - 100€ = 900€).
      * Calcula el nuevo IVA (21%) y el nuevo IRPF (15%) sobre esa base de 900€.
   5. Firma y Validación: Genera el archivo, fírmalo con Autofirma y pásalo por el Validador de FACe.

Resultado esperado:
El alumno debe obtener un nuevo archivo .xsig que contenga el bloque CorrectiveDescriptor (los datos de la rectificación) y un total de factura de 954€ (900 + 189 - 135).


## ✅ Hoja de Solución: Ejercicio 5 (Factura Rectificativa)
Esta hoja sirve para validar que la factura rectificativa generada en el taller cumple con los requisitos legales y los cálculos matemáticos exactos.

------------------------------
## 1. Datos Técnicos de la Rectificación
Para que la factura sea válida en el sistema FACe, el archivo debe contener:

* Tipo de documento: Factura Rectificativa.
* Motivo de rectificación: 02 (Cálculo de importes).
* Referencia Obligatoria: Número y fecha de la factura del Ejercicio 3.
* Método de rectificación: Por sustitución (Importes totales correctos).

------------------------------
## 2. Desglose de Cálculos (Paso a Paso)

| Concepto | Cálculo | Importe |
|---|---|---|
| Base Imponible Original | - | 1.000,00 € |
| Descuento (10%) | 1.000 x 0,10 | - 100,00 € |
| Nueva Base Imponible | 1.000 - 100 | 900,00 € |
| IVA (21%) | 900 x 0,21 | + 189,00 € |
| Retención IRPF (15%) | 900 x 0,15 | - 135,00 € |
| TOTAL FACTURA | 900 + 189 - 135 | 954,00 € |

------------------------------
## 3. Verificación de Seguridad
Antes de dar el ejercicio por apto, el alumno debe confirmar:

   1. ¿El total es 954,00 €? Si es 954,10 € o similar, hay un error de redondeo en la configuración del software.
   2. ¿Ha pasado Autofirma? El archivo final debe tener la extensión .xsig.
   3. ¿Validación FACe? Al subirlo al validador oficial, no debe mostrar alertas en rojo.

------------------------------
## 🚩 Errores comunes encontrados en este ejercicio:

* Error A: Calcular el IRPF sobre el total con IVA (Recuerda: los impuestos y retenciones siempre se calculan sobre la Base Imponible de 900€).
* Error B: No indicar el número de la factura que se rectifica (Sin esto, el ayuntamiento nunca sabrá qué factura estás anulando).
* Error C: Olvidar restar la retención (El IRPF siempre resta del total a cobrar).

------------------------------

