# 🛠️ Ejercicios Prácticos: Gestión con Facturae (Datos Predeterminados)

> **Nota:** Si no dispones de certificado digital, puedes completar los ejercicios guardando los documentos en estado **"Borrador"** o **"Generada"**. No podrás realizar el paso final de "Firmar", pero sí exportar el archivo XML para validarlo.

---

## Ejercicio 1: Configuración de la Base de Datos 🗄️

Antes de generar facturas, debes registrar a los intervinientes con los siguientes datos exactos:

### 1.1 Alta de Emisor (Tu Empresa)
*   **Nombre/Razón Social:** Soluciones Digitales S.L.
*   **CIF:** B12345678
*   **Dirección:** Calle Mayor 10, 28001, Madrid

### 1.2 Alta de Cliente (Administración Pública)
*   **Nombre:** Ayuntamiento de Madrid
*   **CIF:** P2807900B
*   **Centros Administrativos (DIR3):** (Obligatorios para el envío a través de **FACe**)
    *   **Oficina Contable:** L01280796 (Intervención del Ayuntamiento)
    *   **Órgano Gestor:** L01280796 (Ayuntamiento de Madrid)
    *   **Unidad Tramitadora:** L01280796 (Servicios Centrales)

### 1.3 Alta de Producto
*   **Nombre:** Pack Auditoría Digital Nivel 1
*   **Código:** AUD-001
*   **Precio Unitario:** 450,00 €

---

## Ejercicio 2: Creación de una Factura Estándar ✍️

Genera una factura siguiendo estas instrucciones:

1.  **Número de factura:** 2026/001.
2.  **Fecha:** La fecha del día de hoy.
3.  **Línea de detalle:** Añade **2 unidades** del producto "Pack Auditoría Digital Nivel 1".
4.  **Impuestos:** Aplica un **IVA del 21%**.
5.  **Descuento:** Aplica un descuento de **50,00 €** (en valor absoluto, no porcentaje) sobre el total de la base imponible.
6.  **Estado:** Haz clic en **"Guardar"**. Verifica que el estado de la factura sea **"Borrador"**.
7.  **Visualización:** Pulsa el botón "Visualizar" y comprueba que el **Total Factura** sea **1.028,50 €**.

---

## Ejercicio 3: La Factura Rectificativa 🔄

Imagina que el cliente te indica que solo debías facturar **1 unidad** en lugar de 2.

1.  Busca la factura 2026/001 en el listado y selecciona **"Rectificar"**.
2.  **Tipo de rectificación:** Elige "Rectificación por error en cantidades".
3.  **Descripción:** Escribe: "Ajuste de unidades según contrato actualizado".
4.  Modifica la cantidad a **1 unidad**.
5.  Comprueba que se genera una nueva factura (ej. R2026/001) que referencia a la original.

---

## Ejercicio 4: Exportación y Validación Técnica 📄

Este paso es vital para entender qué ocurre "detrás" de la pantalla:

1.  Selecciona tu factura borrador (2026/001) y elige la opción **"Generar Factura"**. (Si te pide firma y no tienes, simplemente dale a cancelar o exportar sin firma).
2.  Exporta el archivo a tu escritorio con el nombre `ejercicio_facturae.xml`.
3.  Accede a la web oficial de validación de FACe: [face.gob.es/es/facturas/validar-facturad](https://face.gob.es/es/facturas/validar-facturad).
4.  Sube tu archivo y comprueba el resultado. Debería dar un error relativo a la **"Firma electrónica"**, pero validar correctamente la **"Estructura XML"**.

---

## Ejercicio 5: Adjuntos y Verificación XML 🖇️

1.  Crea un archivo de texto vacío en tu ordenador llamado `memoria_tecnica.txt`.
2.  En la factura que tienes en borrador, ve a la pestaña **"Adjuntos"** e inserta este archivo.
3.  Guarda los cambios y utiliza la función **"Ver XML"**.
4.  Usa el buscador (Ctrl+F) dentro del código XML para localizar la etiqueta `<AdditionalData>`. AhíAquí tienes los ejercicios para practicar con la **Aplicación de Escritorio Facturae**, utilizando datos específicos para que todos los alumnos trabajen sobre una base común. Esto facilita enormemente la corrección y asegura que se toquen los puntos clave (como los códigos DIR3).

---

# 🛠️ Ejercicios Prácticos: Gestión con Facturae (Datos Predeterminados)

> **Nota para alumnos:** Si no dispones de certificado digital, puedes completar los ejercicios guardando los documentos en estado **"Borrador"** o **"Generada"**. No podrás realizar el paso final de "Firmar", pero sí exportar el archivo XML para validarlo.

---

## Ejercicio 1: Configuración de la Base de Datos 🗄️

Antes de generar facturas, debes registrar a los intervinientes con los siguientes datos exactos:

### 1.1 Alta de Emisor (Tu Empresa)
*   **Nombre/Razón Social:** Soluciones Digitales S.L.
*   **CIF:** B12345678
*   **Dirección:** Calle Mayor 10, 28001, Madrid

### 1.2 Alta de Cliente (Administración Pública)
*   **Nombre:** Ayuntamiento de Madrid
*   **CIF:** P2807900B
*   **Centros Administrativos (DIR3):** (Obligatorios para el envío a través de **FACe**)
    *   **Oficina Contable:** L01280796 (Intervención del Ayuntamiento)
    *   **Órgano Gestor:** L01280796 (Ayuntamiento de Madrid)
    *   **Unidad Tramitadora:** L01280796 (Servicios Centrales)

### 1.3 Alta de Producto
*   **Nombre:** Pack Auditoría Digital Nivel 1
*   **Código:** AUD-001
*   **Precio Unitario:** 450,00 €

---

## Ejercicio 2: Creación de una Factura Estándar ✍️

Genera una factura siguiendo estas instrucciones:

1.  **Número de factura:** 2026/001.
2.  **Fecha:** La fecha del día de hoy.
3.  **Línea de detalle:** Añade **2 unidades** del producto "Pack Auditoría Digital Nivel 1".
4.  **Impuestos:** Aplica un **IVA del 21%**.
5.  **Descuento:** Aplica un descuento de **50,00 €** (en valor absoluto, no porcentaje) sobre el total de la base imponible.
6.  **Estado:** Haz clic en **"Guardar"**. Verifica que el estado de la factura sea **"Borrador"**.
7.  **Visualización:** Pulsa el botón "Visualizar" y comprueba que el **Total Factura** sea **1.028,50 €**.

---

## Ejercicio 3: La Factura Rectificativa 🔄

Imagina que el cliente te indica que solo debías facturar **1 unidad** en lugar de 2.

1.  Busca la factura 2026/001 en el listado y selecciona **"Rectificar"**.
2.  **Tipo de rectificación:** Elige "Rectificación por error en cantidades".
3.  **Descripción:** Escribe: "Ajuste de unidades según contrato actualizado".
4.  Modifica la cantidad a **1 unidad**.
5.  Comprueba que se genera una nueva factura (ej. R2026/001) que referencia a la original.

---

## Ejercicio 4: Exportación y Validación Técnica 📄

Este paso es vital para entender qué ocurre "detrás" de la pantalla:

1.  Selecciona tu factura borrador (2026/001) y elige la opción **"Generar Factura"**. (Si te pide firma y no tienes, simplemente dale a cancelar o exportar sin firma).
2.  Exporta el archivo a tu escritorio con el nombre `ejercicio_facturae.xml`.
3.  Accede a la web oficial de validación de FACe: [face.gob.es/es/facturas/validar-facturad](https://face.gob.es/es/facturas/validar-facturad).
4.  Sube tu archivo y comprueba el resultado. Debería dar un error relativo a la **"Firma electrónica"**, pero validar correctamente la **"Estructura XML"**.

---

## Ejercicio 5: Adjuntos y Verificación XML 🖇️

1.  Crea un archivo de texto vacío en tu ordenador llamado `memoria_tecnica.txt`.
2.  En la factura que tienes en borrador, ve a la pestaña **"Adjuntos"** e inserta este archivo.
3.  Guarda los cambios y utiliza la función **"Ver XML"**.
4.  Usa el buscador (Ctrl+F) dentro del código XML para localizar la etiqueta `<AdditionalData>`. Ahí verás cómo la aplicación codifica tu archivo adjunto para que viaje dentro de la facturaAquí tienes los ejercicios para practicar con la **Aplicación de Escritorio Facturae**, utilizando datos específicos para que todos los alumnos trabajen sobre una base común. Esto facilita enormemente la corrección y asegura que se toquen los puntos clave (como los códigos DIR3).

---

# 🛠️ Ejercicios Prácticos: Gestión con Facturae (Datos Predeterminados)

> **Nota para alumnos:** Si no dispones de certificado digital, puedes completar los ejercicios guardando los documentos en estado **"Borrador"** o **"Generada"**. No podrás realizar el paso final de "Firmar", pero sí exportar el archivo XML para validarlo.

---

## Ejercicio 1: Configuración de la Base de Datos 🗄️

Antes de generar facturas, debes registrar a los intervinientes con los siguientes datos exactos:

### 1.1 Alta de Emisor (Tu Empresa)
*   **Nombre/Razón Social:** Soluciones Digitales S.L.
*   **CIF:** B12345678
*   **Dirección:** Calle Mayor 10, 28001, Madrid

### 1.2 Alta de Cliente (Administración Pública)
*   **Nombre:** Ayuntamiento de Madrid
*   **CIF:** P2807900B
*   **Centros Administrativos (DIR3):** (Obligatorios para el envío a través de **FACe**)
    *   **Oficina Contable:** L01280796 (Intervención del Ayuntamiento)
    *   **Órgano Gestor:** L01280796 (Ayuntamiento de Madrid)
    *   **Unidad Tramitadora:** L01280796 (Servicios Centrales)

### 1.3 Alta de Producto
*   **Nombre:** Pack Auditoría Digital Nivel 1
*   **Código:** AUD-001
*   **Precio Unitario:** 450,00 €

---

## Ejercicio 2: Creación de una Factura Estándar ✍️

Genera una factura siguiendo estas instrucciones:

1.  **Número de factura:** 2026/001.
2.  **Fecha:** La fecha del día de hoy.
3.  **Línea de detalle:** Añade **2 unidades** del producto "Pack Auditoría Digital Nivel 1".
4.  **Impuestos:** Aplica un **IVA del 21%**.
5.  **Descuento:** Aplica un descuento de **50,00 €** (en valor absoluto, no porcentaje) sobre el total de la base imponible.
6.  **Estado:** Haz clic en **"Guardar"**. Verifica que el estado de la factura sea **"Borrador"**.
7.  **Visualización:** Pulsa el botón "Visualizar" y comprueba que el **Total Factura** sea **1.028,50 €**.

---

## Ejercicio 3: La Factura Rectificativa 🔄

Imagina que el cliente te indica que solo debías facturar **1 unidad** en lugar de 2.

1.  Busca la factura 2026/001 en el listado y selecciona **"Rectificar"**.
2.  **Tipo de rectificación:** Elige "Rectificación por error en cantidades".
3.  **Descripción:** Escribe: "Ajuste de unidades según contrato actualizado".
4.  Modifica la cantidad a **1 unidad**.
5.  Comprueba que se genera una nueva factura (ej. R2026/001) que referencia a la original.

---

## Ejercicio 4: Exportación y Validación Técnica 📄

Este paso es vital para entender qué ocurre "detrás" de la pantalla:

1.  Selecciona tu factura borrador (2026/001) y elige la opción **"Generar Factura"**. (Si te pide firma y no tienes, simplemente dale a cancelar o exportar sin firma).
2.  Exporta el archivo a tu escritorio con el nombre `ejercicio_facturae.xml`.
3.  Accede a la web oficial de validación de FACe: [face.gob.es/es/facturas/validar-facturad](https://face.gob.es/es/facturas/validar-facturad).
4.  Sube tu archivo y comprueba el resultado. Debería dar un error relativo a la **"Firma electrónica"**, pero validar correctamente la **"Estructura XML"**.

---

## Ejercicio 5: Adjuntos y Verificación XML 🖇️

1.  Crea un archivo de texto vacío en tu ordenador llamado `memoria_tecnica.txt`.
2.  En la factura que tienes en borrador, ve a la pestaña **"Adjuntos"** e inserta este archivo.
3.  Guarda los cambios y utiliza la función **"Ver XML"**.
4.  Usa el buscador (Ctrl+F) dentro del código XML para localizar la etiqueta `<AdditionalData>`. Ahí verás cómo la aplicación codifica tu archivo adjunto para que viaje dentro de la factura.

---

### 📥 Formato de entregaAquí tienes los ejercicios para practicar con la **Aplicación de Escritorio Facturae**, utilizando datos específicos para que todos los alumnos trabajen sobre una base común. Esto facilita enormemente la corrección y asegura que se toquen los puntos clave (como los códigos DIR3).

---

# 🛠️ Ejercicios Prácticos: Gestión con Facturae (Datos Predeterminados)

> **Nota para alumnos:** Si no dispones de certificado digital, puedes completar los ejercicios guardando los documentos en estado **"Borrador"** o **"Generada"**. No podrás realizar el paso final de "Firmar", pero sí exportar el archivo XML para validarlo.

---

## Ejercicio 1: Configuración de la Base de Datos 🗄️

Antes de generar facturas, debes registrar a los intervinientes con los siguientes datos exactos:

### 1.1 Alta de Emisor (Tu Empresa)
*   **Nombre/Razón Social:** Soluciones Digitales S.L.
*   **CIF:** B12345678
*   **Dirección:** Calle Mayor 10, 28001, Madrid

### 1.2 Alta de Cliente (Administración Pública)
*   **Nombre:** Ayuntamiento de Madrid
*   **CIF:** P2807900B
*   **Centros Administrativos (DIR3):** (Obligatorios para el envío a través de **FACe**)
    *   **Oficina Contable:** L01280796 (Intervención del Ayuntamiento)
    *   **Órgano Gestor:** L01280796 (Ayuntamiento de Madrid)
    *   **Unidad Tramitadora:** L01280796 (Servicios Centrales)

### 1.3 Alta de Producto
*   **Nombre:** Pack Auditoría Digital Nivel 1
*   **Código:** AUD-001
*   **Precio Unitario:** 450,00 €

---

## Ejercicio 2: Creación de una Factura Estándar ✍️

Genera una factura siguiendo estas instrucciones:

1.  **Número de factura:** 2026/001.
2.  **Fecha:** La fecha del día de hoy.
3.  **Línea de detalle:** Añade **2 unidades** del producto "Pack Auditoría Digital Nivel 1".
4.  **Impuestos:** Aplica un **IVA del 21%**.
5.  **Descuento:** Aplica un descuento de **50,00 €** (en valor absoluto, no porcentaje) sobre el total de la base imponible.
6.  **Estado:** Haz clic en **"Guardar"**. Verifica que el estado de la factura sea **"Borrador"**.
7.  **Visualización:** Pulsa el botón "Visualizar" y comprueba que el **Total Factura** sea **1.028,50 €**.

---

## Ejercicio 3: La Factura Rectificativa 🔄

Imagina que el cliente te indica que solo debías facturar **1 unidad** en lugar de 2.

1.  Busca la factura 2026/001 en el listado y selecciona **"Rectificar"**.
2.  **Tipo de rectificación:** Elige "Rectificación por error en cantidades".
3.  **Descripción:** Escribe: "Ajuste de unidades según contrato actualizado".
4.  Modifica la cantidad a **1 unidad**.
5.  Comprueba que se genera una nueva factura (ej. R2026/001) que referencia a la original.

---

## Ejercicio 4: Exportación y Validación Técnica 📄

Este paso es vital para entender qué ocurre "detrás" de la pantalla:

1.  Selecciona tu factura borrador (2026/001) y elige la opción **"Generar Factura"**. (Si te pide firma y no tienes, simplemente dale a cancelar o exportar sin firma).
2.  Exporta el archivo a tu escritorio con el nombre `ejercicio_facturae.xml`.
3.  Accede a la web oficial de validación de FACe: [face.gob.es/es/facturas/validar-facturad](https://face.gob.es/es/facturas/validar-facturad).
4.  Sube tu archivo y comprueba el resultado. Debería dar un error relativo a la **"Firma electrónica"**, pero validar correctamente la **"Estructura XML"**.

---

## Ejercicio 5: Adjuntos y Verificación XML 🖇️

1.  Crea un archivo de texto vacío en tu ordenador llamado `memoria_tecnica.txt`.
2.  En la factura que tienes en borrador, ve a la pestaña **"Adjuntos"** e inserta este archivo.
3.  Guarda los cambios y utiliza la función **"Ver XML"**.
4.  Usa el buscador (Ctrl+F) dentro del código XML para localizar la etiqueta `<AdditionalData>`. Ahí verás cómo la aplicación codifica tu archivo adjunto para que viaje dentro de la factura.

---

### 📥 Formato de entrega sugerido
*   **Captura 1:** Pantallazo del listado de facturas donde aparezcan la factura original y la rectificativa.
*   **Aquí tienes los ejercicios para practicar con la **Aplicación de Escritorio Facturae**, utilizando datos específicos para que todos los alumnos trabajen sobre una base común. Esto facilita enormemente la corrección y asegura que se toquen los puntos clave (como los códigos DIR3).

---

# 🛠️ Ejercicios Prácticos: Gestión con Facturae (Datos Predeterminados)

> **Nota para alumnos:** Si no dispones de certificado digital, puedes completar los ejercicios guardando los documentos en estado **"Borrador"** o **"Generada"**. No podrás realizar el paso final de "Firmar", pero sí exportar el archivo XML para validarlo.

---

## Ejercicio 1: Configuración de la Base de Datos 🗄️

Antes de generar facturas, debes registrar a los intervinientes con los siguientes datos exactos:

### 1.1 Alta de Emisor (Tu Empresa)
*   **Nombre/Razón Social:** Soluciones Digitales S.L.
*   **CIF:** B12345678
*   **Dirección:** Calle Mayor 10, 28001, Madrid

### 1.2 Alta de Cliente (Administración Pública)
*   **Nombre:** Ayuntamiento de Madrid
*   **CIF:** P2807900B
*   **Centros Administrativos (DIR3):** (Obligatorios para el envío a través de **FACe**)
    *   **Oficina Contable:** L01280796 (Intervención del Ayuntamiento)
    *   **Órgano Gestor:** L01280796 (Ayuntamiento de Madrid)
    *   **Unidad Tramitadora:** L01280796 (Servicios Centrales)

### 1.3 Alta de Producto
*   **Nombre:** Pack Auditoría Digital Nivel 1
*   **Código:** AUD-001
*   **Precio Unitario:** 450,00 €

---

## Ejercicio 2: Creación de una Factura Estándar ✍️

Genera una factura siguiendo estas instrucciones:

1.  **Número de factura:** 2026/001.
2.  **Fecha:** La fecha del día de hoy.
3.  **Línea de detalle:** Añade **2 unidades** del producto "Pack Auditoría Digital Nivel 1".
4.  **Impuestos:** Aplica un **IVA del 21%**.
5.  **Descuento:** Aplica un descuento de **50,00 €** (en valor absoluto, no porcentaje) sobre el total de la base imponible.
6.  **Estado:** Haz clic en **"Guardar"**. Verifica que el estado de la factura sea **"Borrador"**.
7.  **Visualización:** Pulsa el botón "Visualizar" y comprueba que el **Total Factura** sea **1.028,50 €**.

---

## Ejercicio 3: La Factura Rectificativa 🔄

Imagina que el cliente te indica que solo debías facturar **1 unidad** en lugar de 2.

1.  Busca la factura 2026/001 en el listado y selecciona **"Rectificar"**.
2.  **Tipo de rectificación:** Elige "Rectificación por error en cantidades".
3.  **Descripción:** Escribe: "Ajuste de unidades según contrato actualizado".
4.  Modifica la cantidad a **1 unidad**.
5.  Comprueba que se genera una nueva factura (ej. R2026/001) que referencia a la original.

---

## Ejercicio 4: Exportación y Validación Técnica 📄

Este paso es vital para entender qué ocurre "detrás" de la pantalla:

1.  Selecciona tu factura borrador (2026/001) y elige la opción **"Generar Factura"**. (Si te pide firma y no tienes, simplemente dale a cancelar o exportar sin firma).
2.  Exporta el archivo a tu escritorio con el nombre `ejercicio_facturae.xml`.
3.  Accede a la web oficial de validación de FACe: [face.gob.es/es/facturas/validar-facturad](https://face.gob.es/es/facturas/validar-facturad).
4.  Sube tu archivo y comprueba el resultado. Debería dar un error relativo a la **"Firma electrónica"**, pero validar correctamente la **"Estructura XML"**.

---

## Ejercicio 5: Adjuntos y Verificación XML 🖇️

1.  Crea un archivo de texto vacío en tu ordenador llamado `memoria_tecnica.txt`.
2.  En la factura que tienes en borrador, ve a la pestaña **"Adjuntos"** e inserta este archivo.
3.  Guarda los cambios y utiliza la función **"Ver XML"**.
4.  Usa el buscador (Ctrl+F) dentro del código XML para localizar la etiqueta `<AdditionalData>`. Ahí verás cómo la aplicación codifica tu archivo adjunto para que viaje dentro de la factura.

---

### 📥 Formato de entrega sugerido
*   **Captura 1:** Pantallazo del listado de facturas donde aparezcan la factura original y la rectificativa.
*   **Captura 2:** Resultado del validador de FACe.
*   **Archivo:** El XML generado en el ejercicio 4.</AdditionalData></AdditionalData></AdditionalData></AdditionalData></AdditionalData></AdditionalData>
