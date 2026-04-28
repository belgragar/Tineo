# 📜 Capítulo 2: El Certificado Electrónico

Si la firma electrónica es la "acción" de firmar, el **Certificado Electrónico** es el "documento de identidad" digital que nos permite realizar esa acción con garantías legales.

---

## 2.1 Certificado electrónico 🆔
Es un documento electrónico firmado por un Prestador de Servicios de Certificación que vincula unos **datos de verificación de firma** a un **firmante** y confirma su identidad. 

### 2.1.1 Las claves digitales 🔑
El certificado se basa en la **criptografía asimétrica**, que utiliza un par de claves:
* **Clave Privada:** Solo la conoce el titular. Se utiliza para **firmar** documentos. Debe custodiarse con máxima seguridad.
* **Clave Pública:** Es accesible para todo el mundo. Se utiliza para **verificar** que la firma fue realizada por el titular y que el documento no ha sido alterado.



[Image of Public and Private Key Cryptography]


### 2.1.2 Tipos de certificados 👥
Dependiendo de quién sea el titular y su propósito:
* **Persona Física:** Para ciudadanos individuales (ej. el certificado de la FNMT de ciudadano).
* **Representante:** Para personas que actúan en nombre de una entidad jurídica (empresa, asociación).
* **Administración Pública:** Específicos para el personal al servicio de las administraciones.
* **Sello Electrónico:** Para actuaciones administrativas automatizadas (sin intervención humana directa).

---

## 2.2 Entidades emisoras de certificado electrónico 🏢
También llamadas **Autoridades de Certificación (CA)**. Son terceros de confianza encargados de verificar la identidad del solicitante antes de emitir el certificado.
* **Ejemplos en España:** FNMT-RCM (Fábrica Nacional de Moneda y Timbre), Autoridades de Certificación de las Comunidades Autónomas, Cámaras de Comercio (Camerfirma), y el propio Ministerio del Interior (DNIe).

## 2.3 Procedimiento de obtención de un certificado electrónico 🛠️
Aunque puede variar según el emisor, el proceso estándar suele ser:
1.  **Solicitud vía web:** Se solicita el código de descarga desde el navegador.
2.  **Acreditación de la identidad:** El paso más importante. El usuario debe acudir **físicamente** a una Oficina de Registro (o mediante sistemas de video-identificación autorizados) para demostrar que es quien dice ser.
3.  **Descarga e instalación:** Una vez acreditado, se descarga el certificado en el mismo equipo donde se realizó la solicitud o se activa en la tarjeta inteligente.

## 2.4 La confidencialidad del certificado electrónico 🛡️
La seguridad del sistema depende totalmente de que la **clave privada** no sea comprometida.
* **Contraseñas:** El certificado suele estar protegido por un PIN o contraseña de uso.
* **Copia de seguridad:** Es vital exportar el certificado (formato .pfx o .p12) con contraseña y guardarlo en un lugar seguro fuera del equipo principal.

---

## 2.5 Extinción de la vigencia del certificado electrónico ⌛
Un certificado deja de ser válido por dos motivos principales:
1.  **Caducidad:** Todos los certificados tienen una fecha de fin de validez (normalmente entre 2 y 4 años).
2.  **Revocación:** Anulación definitiva antes de la fecha de caducidad por causas como:
    * Pérdida o robo del dispositivo donde estaba el certificado.
    * Compromiso de la clave privada (sospecha de que alguien la conoce).
    * Cambio en los datos del titular (ej. cambio de apellidos o de cargo en la empresa).
    * Cese de la actividad de la entidad certificadora.

---

## 2.6 Certificados reconocidos 🎖️
Bajo el marco del Reglamento eIDAS y la Ley 6/2020, se denominan **Certificados Cualificados** (antes llamados "reconocidos"). Para que un certificado tenga esta categoría debe:
* Ser expedido por un **Prestador de Servicios de Confianza Cualificado**.
* Cumplir con los requisitos de seguridad técnica establecidos legalmente.
* Estar almacenado, preferiblemente, en un **dispositivo seguro** (como el chip de un DNI electrónico o una tarjeta criptográfica).

---

### 💡 Nota para el alumno
Recuerda que el **DNI electrónico (DNIe)** es, en sí mismo, un contenedor de certificados reconocidos de autenticación y firma, lo que lo convierte en una de las herramientas más potentes y seguras de las que disponemos como ciudadanos.
