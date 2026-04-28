# 📑 Capítulo 1: La Firma Electrónica

La firma electrónica es el pilar fundamental de la digitalización administrativa y comercial. No es solo un "garabato digital", sino un conjunto de datos que garantizan quién firma y que lo firmado no ha sido alterado.

---

## 1.1 Régimen jurídico aplicable ⚖️
El marco legal se asienta sobre dos pilares principales:
* **Reglamento (UE) Nº 910/2014 (eIDAS):** La norma suprema a nivel europeo que garantiza la interoperabilidad entre países miembros.
* **Ley 6/2020 (España):** Regula aspectos específicos de los servicios de confianza electrónica, complementando al eIDAS y derogando la antigua Ley 59/2003.

## 1.2 Concepto 💡
La firma electrónica se define como el conjunto de datos en forma electrónica consignados junto a otros datos electrónicos o asociados plenamente con ellos, que utiliza el firmante para firmar. Su función es equivalente a la firma manuscrita: **identificar al autor y asegurar su conformidad.**

## 1.3 Tipos de firma 🖋️
Existen tres niveles de seguridad según el Reglamento eIDAS:
1.  **Firma Electrónica Simple:** Datos asociados que el firmante utiliza para firmar (ej. un PIN o un "Acepto").
2.  **Firma Electrónica Avanzada:** Debe estar vinculada al firmante de manera única, permitir su identificación, haber sido creada con datos bajo su control exclusivo y permitir detectar cualquier modificación posterior del documento.
3.  **Firma Electrónica Cualificada:** Es una firma avanzada creada mediante un **dispositivo cualificado** y basada en un **certificado cualificado**. Tiene el mismo valor jurídico que una firma manuscrita.



## 1.4 Usos 🚀
* **Relación con la Administración:** Liquidación de impuestos, solicitud de subvenciones, consulta de vida laboral.
* **Ámbito Comercial:** Firma de contratos, facturación electrónica (obligatoria en B2G y próximamente en B2B), presupuestos.
* **Ámbito Privado:** Firma de contratos de alquiler, seguros o banca online.

## 1.5 Formatos 📂
Para que los documentos sean legibles y válidos a largo plazo, se usan formatos estándar:
* **PAdES (PDF):** Ideal para documentos que deben ser leídos por personas (el más común).
* **XAdES (XML):** Común en facturación electrónica y procesos automatizados.
* **CAdES (Binario):** Para firmas de archivos de gran tamaño.

## 1.6 Dispositivos de firma 🛠️
Son los medios físicos o lógicos donde se almacenan las claves de firma.
### 1.6.1 y 1.6.2 Dispositivo seguro de creación de firma (QSCD)
Para que una firma sea **cualificada**, el dispositivo debe cumplir requisitos estrictos:
* Garantizar la confidencialidad de la clave.
* Protección contra falsificaciones.
* El contenido firmado no puede ser alterado antes de la firma.
* *Ejemplos:* Tarjetas inteligentes (DNIe), tokens USB criptográficos o sistemas en la nube (HSM) custodiados por prestadores cualificados.

---

## 1.7 Certificación de prestadores y dispositivos 🛡️
No cualquier empresa puede emitir certificados cualificados. Deben pasar auditorías estrictas y estar incluidas en la **TSL (Trusted Service List)** de su país. El Ministerio de Asuntos Económicos y Transformación Digital supervisa a estos prestadores en España.

## 1.8 La firma electrónica como medio de prueba en un juicio ⚖️🔨
### 1.8.1 Valor probatorio
* La firma **cualificada** goza de una presunción de autenticidad: si alguien la impugna, debe demostrar que es falsa (inversión de la carga de la prueba).
* La firma **avanzada o simple** es admisible, pero si se impugna, el firmante debe aportar pruebas periciales que demuestren su validez.

### 1.8.2 Presupuestos generales
Para que sea válida en juicio, debe garantizarse la **integridad** (que no cambió) y la **autenticidad** (quién lo hizo).

### 1.8.3 Cómo aportar pruebas digitales
No basta con imprimir el documento. Se debe aportar:
1.  El **archivo digital** original.
2.  El **certificado** de firma.
3.  Si es necesario, un **dictamen pericial informático** que explique la trazabilidad de la firma.

---

## 1.9 Documentos firmados electrónicamente 📄
Un documento firmado es un archivo informático que contiene el documento original + la firma (un hash cifrado). Si se cambia una sola coma del texto original, la firma se rompe y deja de ser válida.

## 1.10 Servicios de certificación 🌐
Son servicios prestados por entidades de confianza, tales como:
* Emisión de certificados electrónicos.
* **Sellado de tiempo (Timestamping):** Garantiza que un dato existía en un momento dado y no ha sido alterado.
* Validación de firmas.

## 1.11 Concepto de prestadores de servicios de confianza 🏢
Son personas físicas o jurídicas que prestan uno o varios servicios de confianza. Se dividen en:
* **No cualificados:** Cumplen normas básicas.
* **Cualificados:** Cumplen los requisitos más exigentes del eIDAS y sus firmas tienen el máximo reconocimiento legal automático en toda la UE.

## 1.12 Infringimientos y sanciones ⚠️
La Ley 6/2020 establece un régimen sancionador para los prestadores:
* **Leves:** Multas de hasta 2.000€.
* **Graves:** Multas de 2.001€ a 150.000€.
* **Muy graves:** Multas de 150.001€ a 300.000€ (ej. emitir certificados cualificados sin ser prestador acreditado o incumplir medidas de seguridad críticas).
