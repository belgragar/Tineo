# 📑 Capítulo 5: La Facturación Electrónica

Este tema profundiza en el estándar de facturación en España y el uso de la aplicación oficial del Ministerio para la gestión de facturas digitales.

---

## 5.1 Introducción. Legislación ⚖️
La factura electrónica es un documento digital que tiene los mismos efectos legales que una factura en papel.
*   **Ley 25/2013:** Obliga al uso de factura electrónica en relaciones con la Administración Pública (B2G).
*   **Ley Crea y Crece (2022):** Amplía la obligación de la factura electrónica a todas las relaciones entre empresas y autónomos (B2B), con un despliegue progresivo según facturación.
*   **Requisitos:** Para ser válida, debe garantizar la **autenticidad del origen**, la **integridad del contenido** y la **legibilidad**.

## 5.2 Formato Facturae 🏗️
El estándar técnico en España es el formato **Facturae**, basado en el lenguaje **XML**.
*   Es un formato estructurado que permite el tratamiento automatizado por parte de los sistemas informáticos.
*   Las versiones más comunes son la **3.2.1** y la **3.2.2**.

## 5.3 Aplicación Facturae 💻
Es la aplicación gratuita de escritorio ofrecida por el Ministerio de Industria para generar y gestionar facturas sin necesidad de un software privado.

### 5.3.1 Operaciones específicas
La aplicación permite gestionar el ciclo de vida completo de una factura:
*   **5.3.1.1 Visualizar:** Ver los datos de la factura en una interfaz amigable antes de procesarla.
*   **5.3.1.2 Editar:** Modificar datos sólo en facturas que aún están en estado de "Borrador".
*   **5.3.1.3 Rectificar:** Crear una factura rectificativa para corregir errores en una factura ya emitida y enviada.
*   **5.3.1.4 Ver rectificaciones:** Consultar el historial de facturas correctoras asociadas a una original.
*   **5.3.1.5 Adjuntos:** Incluir documentación adicional (PDF, imágenes) dentro del archivo XML.
*   **5.3.1.6 Firmar:** Aplicar la firma electrónica mediante certificado digital para dar validez legal al documento.
*   **5.3.1.7 Enviar / Reenviar:** Conexión directa con los puntos generales de entrada (como FACe) o envío por correo electrónico.
*   **5.3.1.8 Anular factura:** Solicitar la anulación de una factura enviada por error.
*   **5.3.1.9 Ver el XML:** Acceso al código fuente de la factura para comprobaciones técnicas.
*   **5.3.1.10 Visualizar formato Facturae:** Uso de hojas de estilo para convertir el XML en un documento legible.
*   **5.3.1.11 Imprimir:** Generar una copia en papel (o PDF) para archivo físico.
*   **5.3.1.12 Eliminar borradores:** Limpieza de documentos que no llegaron a emitirse.

### 5.3.2 Generación de facturas ✍️
Proceso de introducción de datos: emisor, receptor, líneas de detalle (artículos/servicios) e impuestos (IVA, IRPF).

### 5.3.3 Guardar borrador 💾
Permite salvar el trabajo realizado sin necesidad de finalizar o firmar la factura en el momento.

### 5.3.4 Firmar y enviar factura 🚀
Paso final donde se selecciona el certificado digital, se sella el documento y se remite al Punto General de Entrada de Facturas Electrónicas.

### 5.3.5 Recibir factura 📩
La aplicación permite importar facturas recibidas de proveedores para su gestión y custodia.

### 5.3.6 Importar / Exportar facturas 📥📤
Permite mover facturas entre diferentes instalaciones de la aplicación o realizar copias de seguridad.

### 5.3.7 Importar / Exportar base de datos 🗄️
Funcionalidad para cargar masivamente datos de clientes o productos desde archivos externos (CSV o Excel) para agilizar la creación de facturas.

---

## 5.4 Herramientas avanzadas: PDF417 📊
El **PDF417** es un código de barras bidimensional de alta densidad que se imprime en las facturas.
*   Almacena gran cantidad de información de la factura en un espacio pequeño.
*   Facilita la digitalización y entrada de datos automática mediante escáneres en empresas que aún gestionan parte del proceso en papel.

## 5.5 SII - Suministro Inmediato de Información ⏱️
El **SII** es el sistema de gestión del IVA basado en la llevanza de los Libros Registro a través de la Sede Electrónica de la **AEAT**.
*   **Obligatoriedad:** Para grandes empresas (facturación > 6 millones €), grupos de IVA e inscritos en el REDEME.
*   **Plazo:** Se deben enviar los detalles de las facturas emitidas y recibidas en un plazo de **4 días naturales** desde su expedición o registro contable.

---

**Nota para el alumno:** Aunque la aplicación de escritorio Facturae sigue vigente, la tendencia actual se desplaza hacia plataformas en la nube e interoperabilidad total, tal como marca el nuevo reglamento de la Ley Crea y Crece.
