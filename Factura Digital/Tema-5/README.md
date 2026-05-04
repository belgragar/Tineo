# 📑 Capítulo 5: La Facturación Electrónica

Este tema profundiza en el estándar de facturación en España y el uso de la aplicación oficial del Ministerio para la gestión de facturas digitales.

---

## 5.1 Introducción. Legislación ⚖️
La factura electrónica es un documento digital que tiene los mismos efectos legales que una factura en papel.
*   **Ley 25/2013:** Obliga al uso de factura electrónica en relaciones con la Administración Pública (B2G).
*   **Ley Crea y Crece (2022):** Amplía la obligación de la factura electrónica a todas las relaciones entre empresas y autónomos (B2B), con un despliegue progresivo según facturación.
*   **Requisitos:** Para ser válida, debe garantizar la **autenticidad del origen**, la **integridad del contenido** y la **legibilidad**.

## 5.2 Formato Facturae 🏗️

### 📄 El estándar Facturae
El formato **Facturae** es el estándar técnico definido por el Gobierno de España para la codificación de facturas.
*   **Lenguaje XML:** A diferencia de un PDF (que es una imagen digital), Facturae utiliza lenguaje **XML**. Esto permite que los datos (importes, tipos impositivos, conceptos) sean procesados automáticamente por los sistemas contables sin intervención humana.
*   **Versiones:** Las versiones más utilizadas actualmente son la **3.2.1** y la **3.2.2**. Es crucial seleccionar la versión correcta en la aplicación según los requisitos del receptor.
*   **Firma Electrónica:** Para que un archivo XML sea considerado una "Facturae" válida, debe estar firmado electrónicamente con un certificado cualificado.

### 📮 FACe: El Punto General de Entrada
**FACe** (Punto General de Entrada de Facturas Electrónicas) es la plataforma online que actúa como ventanilla única para el envío de facturas a la Administración Pública.

*   **Ventanilla Única:** Permite enviar facturas a la Administración General del Estado, así como a miles de Ayuntamientos, Comunidades Autónomas y otras instituciones adheridas.
*   **Códigos DIR3:** Es el concepto más importante al usar FACe. Toda factura enviada a través de este portal debe incluir tres códigos de identificación obligatorios:
    1.  **Oficina Contable:** Quien gestiona la contabilidad.
    2.  **Órgano Gestor:** Quien aprueba la factura.
    3.  **Unidad Tramitadora:** Quien recibe el servicio o bien.
*   **Trazabilidad:** FACe permite al proveedor consultar en tiempo real el estado de su factura (si ha sido recibida, registrada, conformada o pagada).
*   **Obligatoriedad:** El uso de FACe es obligatorio para facturas superiores a **5.000 €** destinadas a la Administración, aunque muchas administraciones ya lo exigen para cualquier importe.

> **Nota Práctica:** Cuando generas una factura en la **Aplicación Facturae (5.3)**, el objetivo final es obtener un archivo con extensión `.xsig` (XML firmado) para subirlo manualmente a la web de **FACe** o enviarlo directamente desde el programa si está configurado.

---

### Diferencia clave:
| Concepto | ¿Qué es? | Función |
| :--- | :--- | :--- |
| **Facturae** | El Formato (XML) | Garantiza que los datos estén estructurados y sean legibles por máquinas. |
| **FACe** | El Portal (Buzón) | Es el canal oficial de envío y seguimiento para la Administración Pública. |

## 5.3 Aplicación Facturae 💻
Es la aplicación gratuita de escritorio ofrecida por el Ministerio de Industria para generar y gestionar facturas sin necesidad de un software privado.

Descarga: https://www.facturae.gob.es/

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
