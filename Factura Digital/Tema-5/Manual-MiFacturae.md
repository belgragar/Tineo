# 🌐 Guía de Uso: MiFacturae (Versión Online)

La plataforma **MiFacturae** es la solución web oficial para generar facturas electrónicas (.xml) sin necesidad de instalar software complejo.

---

## 🛠️ Requisitos Previos
1.  **Certificado Digital:** Instalado en tu navegador (FNMT, DNIe).
2.  **Autofirma:** Software necesario para firmar legalmente desde la web. [Descárgalo aquí](https://firmaelectronica.gob.es).
3.  **Códigos DIR3:** Debes conocer los códigos de tu cliente (si es Administración Pública).

---

## 🚀 Paso 1: Acceso y Perfil
*   Entra en [mifacturae.face.gob.es](https://face.gob.es).
*   Identifícate con tu certificado.
*   En **"Mis Datos"**, asegúrate de tener configurado tu IBAN para recibir los cobros.

---

## 🏢 Paso 2: El Receptor y los Códigos DIR3
Al facturar a la Administración Pública, no basta con el CIF. Es obligatorio indicar tres códigos que identifican dónde debe ir el dinero y quién debe aprobarlo:

### 🔍 ¿Qué son los DIR3?
Son tres etiquetas alfanuméricas de 9 caracteres (ej: L01330000):
1.  **Oficina Contable:** Quien gestiona la contabilidad.
2.  **Órgano Gestor:** Quien aprueba la factura.
3.  **Unidad Tramitadora:** Quien recibe el servicio (ej: un departamento concreto).

### 📍 ¿Cómo encontrarlos?
Si no figuran en tu contrato o pedido, puedes buscarlos de dos formas:
*   **Directorio FACe:** En la web de [FACe - Directorio de Unidades](https://face.gob.es) puedes buscar por nombre de ayuntamiento o entidad.
*   **Filtro en MiFacturae:** La propia aplicación permite buscar por nombre del organismo al rellenar los datos del receptor.

> ⚠️ **Nota:** Si un solo código está mal, el sistema FACe rechazará la factura automáticamente.

---

## 📝 Paso 3: Creación de la Factura
1.  **Líneas de Detalle:** Añade el concepto, cantidad y precio. El sistema desglosa el IVA.
2.  **Retenciones:** Si eres autónomo profesional, recuerda activar el **IRPF** en el apartado de impuestos.
3.  **Adjuntos:** Si necesitas incluir un albarán o presupuesto en PDF, hay un apartado de "Documentos anexos".

---

## 🖋️ Paso 4: Firma, Envío y Seguimiento
1.  Pulsa **"Generar y Firmar"**. Se abrirá **Autofirma** para validar el proceso.
2.  **Descarga el archivo:** Guarda el archivo `.xsig` generado (es tu factura original legal).
3.  **Enviar a FACe:** La mayoría de administraciones están conectadas. Envía el archivo directamente desde el portal.
4.  **Estado:** En tu panel de MiFacturae verás si cambia a **"Registrada"**, **"Abonada"** o si ha sido **"Rechazada"** (en cuyo caso indicará el motivo).

---

## 📌 Consejos para el Alumno
*   **No borres el archivo .xsig:** Aunque lo subas a la web, tú debes custodiar el archivo firmado durante 4 años.
*   **Facturas Rectificativas:** Si te equivocas, no borres; debes emitir una "factura rectificativa" que anule la anterior.

---


## ⚠️ Errores Comunes al subir facturas a FACe
Incluso con el archivo generado, el portal de la Administración puede rechazar el envío por los siguientes motivos:

## 1. Códigos DIR3 incorrectos o inexistentes ❌

* El error: Es el más común. Ocurre al confundir la Oficina Contable con la Unidad Tramitadora o al usar códigos obsoletos.
* Solución: Verifica los códigos en el Directorio de Unidades de FACe. Si el organismo es pequeño (un ayuntamiento pedáneo), a veces usa los códigos de una entidad superior (la Diputación).

## 2. Error en la firma electrónica (Formato XAdES) 🖋️

* El error: El portal indica que "la firma no es válida" o "formato de firma no reconocido". Esto suele pasar si se firma el archivo con un programa externo no configurado para el estándar XAdES-EPES que exige Facturae.
* Solución: Utiliza siempre la última versión de Autofirma o firma directamente desde la aplicación MiFacturae.

## 3. Importes que no cuadran (Errores de redondeo) 🧮

* El error: FACe rechaza la factura porque la suma de las bases + impuestos no coincide con el total por una diferencia de céntimos.
* Solución: Revisa que el redondeo se aplique en cada línea de factura y no solo al final. El estándar Facturae es muy estricto con los decimales (máximo dos para el total).

## 4. Falta del número de pedido o expediente 📋

* El error: Muchas administraciones (especialmente las grandes como Ministerios o Comunidades Autónomas) exigen que en el campo "Referencia del Receptor" o "Notas" aparezca el número de contrato o pedido.
* Solución: Pregunta siempre a tu contacto en la Administración si hay algún dato obligatorio que debas incluir en el campo de "Texto libre" o "Referencia de la Factura".

## 5. Intentar subir un PDF en lugar de un XML/XSIG 📄

* El error: Subir la representación visual (el PDF que podemos leer nosotros) en lugar del archivo informático estructurado.
* Solución: Asegúrate de que el archivo que subes termina en .xml o .xsig.

## 6. Certificado digital caducado o revocado 🪪

* El error: El proceso de firma parece funcionar, pero FACe lo rechaza al validar la identidad del emisor.
* Solución: Comprueba la validez de tu certificado en la web de [Valide](https://valide.redsara.es/valide/).


