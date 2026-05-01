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
*Manual para el curso de Facturación Digital - v1.1 (Actualizado con sección DIR3)*
