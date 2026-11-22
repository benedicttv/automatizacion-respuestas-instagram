# Automatización de respuestas de Instagram desde ChatGPT

Una guía en español para construir **tu propia instalación privada**, con tus cuentas de Meta y Firebase, y un complemento personal de ChatGPT.

La idea es sencilla: pedir en ChatGPT «cuando comenten guía en esta publicación, envía mi enlace por DM y responde al comentario». Tu servidor ejecuta la regla mediante webhooks, incluso después de cerrar ChatGPT.

## Empieza aquí

1. Abre **[GUIA-PARA-LA-IA.md](GUIA-PARA-LA-IA.md)** y descárgala con el botón **Raw / Download raw file** de GitHub.
2. Entrégasela a una IA con capacidad de programar y trabajar con tu entorno. Si dispone de navegador, puede ayudarte con los paneles de configuración.
3. Copia este mensaje:

> Quiero construir mi propia instalación privada siguiendo el archivo adjunto. Lee la guía completa, comprueba la documentación oficial vigente, revisa qué herramientas tienes disponibles y empieza por la fase 0. Crea el código y las pruebas necesarios. Avanza con los pasos autorizados y pídeme intervención solo cuando haga falta mi identidad, una autorización, una verificación o una decisión que no puedas inferir. No me pidas claves en el chat. Mantén un registro local para poder continuar otro día.

No se construye una plataforma web: solo un servidor y las pequeñas páginas de acceso, autorización, privacidad y revocación que necesita OAuth.

La guía principal es autocontenida: puedes pasar **solo ese archivo** a la IA. Los archivos de ejemplo de este repositorio son ayudas opcionales.

## Qué puedes construir

- Consultar tus publicaciones y reels desde ChatGPT.
- Preparar automatizaciones con palabra clave.
- Enviar un DM, responder públicamente al comentario o hacer ambas cosas.
- Revisar la propuesta antes de guardarla o activarla.
- Activar y pausar reglas sin consultar mensajes cada minuto.
- Mantener todo el control de las reglas en ChatGPT, sin panel web ni chat web adicional.

## Qué necesitas

- Instagram profesional —empresa o creador— y, para la ruta documentada, una página de Facebook vinculada.
- Tus cuentas y autorizaciones de Meta Developers y Firebase / Google Cloud.
- Una cuenta de ChatGPT con permiso para añadir conexiones MCP personales. La disponibilidad depende de tu cuenta y espacio.
- **No necesitas una cuenta de desarrollador de OpenAI, una API key ni saldo de la API para esta ruta. Se utiliza tu ChatGPT.**

Firebase puede generar costes. La guía incluye controles de consumo y distingue los avisos de presupuesto de los topes de gasto.

## Alcance del repositorio

Este repositorio publica **instrucciones y plantillas**, no una copia del servidor privado original ni una aplicación lista para desplegar. La IA debe generar y probar la implementación en tu entorno. No contiene tokens, claves, conversaciones, cuentas de ejemplo operativas ni acceso al servicio de otra persona.

Puedes consultar, descargar y usar estas instrucciones para trabajar con tus propias cuentas. El complemento que construyas puede seguir siendo privado: publicar esta guía no publica tu plugin en el directorio de ChatGPT.

## Archivos

- [Guía completa para la IA](GUIA-PARA-LA-IA.md).
- [Plantilla de configuración sin secretos](config.example.json).
- [Plantilla del registro local de instalación](ESTADO.example.md).
- [.gitignore](.gitignore) para evitar publicar archivos locales por accidente.

Basado en una instalación real probada en noviembre de 2026. Las interfaces, permisos y versiones cambian: la IA debe verificar los requisitos vigentes y registrar qué pudo comprobar realmente. No se garantiza la aprobación de Meta ni la disponibilidad de funciones de ChatGPT para todas las cuentas.
