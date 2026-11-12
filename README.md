# Microsoft Account Recovery – IT Support Case Study

*(Recuperación de cuenta Microsoft – Caso práctico de soporte técnico)*

## Project Overview

*(Descripción general del caso)*

Este documento presenta la resolución de una incidencia técnica real relacionada con el acceso a un equipo con Windows, cuya única cuenta de usuario estaba vinculada a una cuenta Microsoft.

La autenticación de la cuenta presentaba inconvenientes durante el proceso de verificación de identidad, impidiendo el acceso al sistema operativo.

El objetivo fue recuperar el acceso al equipo sin recurrir al formateo, la reinstalación del sistema operativo ni la pérdida de información.

**Tipo de experiencia:** Consultoría técnica particular – Resolución de una incidencia real.

Este caso corresponde a una intervención técnica realizada a solicitud de una clienta particular. No se trata de un proyecto académico ni de una simulación hipotética, sino de un problema real que fue investigado y resuelto mediante un proceso de diagnóstico y aplicación de distintas alternativas de recuperación.

## Problem Identification

*(Identificación del problema)*

Durante el proceso de acceso al equipo se identificaron las siguientes situaciones:

- La pantalla de inicio de Windows mostraba únicamente la cuenta de la propietaria.
- El acceso requería completar un proceso de verificación mediante un código enviado por correo electrónico.
- Los códigos de verificación presentaban demoras en su recepción.
- Luego de varios intentos, el sistema comenzó a mostrar un mensaje indicando que no era posible enviar el código de verificación.
- El cambio de contraseña se completó correctamente, pero no permitió ingresar porque continuaba siendo necesaria la verificación adicional.

Las evidencias permitieron orientar el diagnóstico hacia un inconveniente en el proceso de autenticación y verificación, y no hacia un error de contraseña.

## Troubleshooting Process

*(Proceso de diagnóstico y resolución de problemas)*

### Step 1 — Password Reset

*(Paso 1 — Restablecimiento de contraseña)*

Se realizó el cambio de contraseña de la cuenta Microsoft.

Aunque el procedimiento finalizó correctamente, Windows continuó solicitando un código de verificación. Al intentar obtenerlo, apareció un mensaje de error que impedía continuar.

Esto permitió descartar, como causa principal, una contraseña incorrecta y continuar investigando el proceso de autenticación.

### Step 2 — Alternative Authentication Method

*(Paso 2 — Método de autenticación alternativo)*

Se intentó utilizar un método alternativo de autenticación mediante un código QR.

Para realizar la prueba, se habilitó Bluetooth tanto en el equipo como en el teléfono de la propietaria. Sin embargo, el intento también fue rechazado y no permitió recuperar el acceso.

### Step 3 — Microsoft Support Escalation

*(Paso 3 — Derivación del caso al soporte técnico de Microsoft)*

Ante la imposibilidad de completar la verificación por los métodos disponibles, se investigaron los canales oficiales de asistencia de Microsoft. 

Para ello, se consiguió un número de soporte ténico oficial , el cual una IA fué la que nos indicó el canal oficial para solucionar este tipo de incidencias 11 6076-0010 , relleando un formulario aka.ms/mssupport .

Se localizó un solucionador de problemas y un formulario de contacto oficial. Para presentar el caso, se preparó una descripción detallada de la incidencia y se recopilaron capturas de pantalla como evidencia, en un documento de Google Docs para enviarlo como link.

La solicitud fue enviada y se obtuvo un número de ticket para su seguimiento.

### Step 4 — Follow-up and Access Restoration

*(Paso 4 — Seguimiento y recuperación del acceso)*

Al día siguiente se recibió una comunicación de Microsoft informando el cierre del caso y haciendo referencia a controles de seguridad más estrictos.

Posteriormente, se volvió a intentar el acceso al equipo utilizando la contraseña actualizada. En esta oportunidad, el sistema permitió continuar con el proceso de verificación.

Se solicitó un nuevo código por correo electrónico, que fue recibido e ingresado correctamente. Finalmente, Windows permitió configurar un nuevo PIN e ingresar al escritorio.

## Results and Validation

*(Resultados y verificación)*

Una vez recuperado el acceso, se realizaron comprobaciones para verificar la integridad del entorno de trabajo:

- Se comprobó que el escritorio y el entorno del sistema permanecían intactos.
- Se verificó que la aplicación de gestión comercial NEX continuaba instalada y accesible.
- Se comprobó que los productos previamente cargados en el sistema seguían disponibles.
- No fue necesario formatear el equipo ni reinstalar Windows.
- No se requirió recuperar información mediante copias de seguridad.

**Resultado:** Se recuperó el acceso al equipo y se verificó que la información y la aplicación de gestión del negocio permanecieran disponibles.

## Technical Skills Applied

*(Habilidades técnicas aplicadas)*

- Diagnóstico y resolución de incidencias técnicas.
- Análisis de problemas de autenticación.
- Identificación y evaluación de posibles causas.
- Prueba de métodos alternativos de acceso.
- Investigación de documentación y canales oficiales de soporte.
- Gestión y seguimiento de solicitudes de asistencia técnica.
- Recopilación y organización de evidencias.
- Verificación de integridad del entorno y de la información.

## Tools and Technologies

*(Herramientas y tecnologías utilizadas)*

- Windows.
- Microsoft Account.
- Correo electrónico.
- Autenticación mediante código de verificación.
- Autenticación alternativa mediante código QR.
- Bluetooth.
- Google Docs.

## Scope and Limitations

*(Alcance y limitaciones)*

La intervención se centró en investigar y resolver el inconveniente de acceso a la cuenta Microsoft vinculada al equipo.

No se tuvo acceso a los registros internos de Microsoft, por lo que no es posible determinar con certeza cuál fue la causa técnica específica del inconveniente ni qué acción interna permitió restablecer el envío de códigos.

La recuperación del acceso se produjo después de la gestión del caso ante el soporte oficial y de un nuevo intento de autenticación.

No se realizaron modificaciones en la base de datos de NEX, reinstalaciones del sistema operativo ni procedimientos de recuperación de archivos.

## Evidence

*(Evidencias)*

Se incluyen capturas de pantalla anonimizadas que documentan parte del proceso:

- `01-authentication-error.jpeg`: mensaje de error presentado durante el intento de envío del código de verificación.
- `02-microsoft-support-response.jpeg`: Mensaje recibido luego de haber enviado la explicación del caso, en el solucionador de problemas.
- 03-`microsoft-support-response.jpeg`: comunicación recibida de Microsoft luego de la apertura del ticket.

## Case Information

*(Información del caso)*

- **Case Classification:** Real IT Support Experience.
- **Experience Type:** Independent Technical Assistance / Private Consultation.
- **Environment:** Windows / Microsoft Account.
- **Application Validated:** NEX.
- **Documentation Type:** Technical Case Study.
- **Privacy:** Personal and confidential information excluded.
