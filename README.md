# caso-1
Caso 1 de Isaac Rojas y Fabricio Picado

# Punto 3

## 1. Registro y autenticación del usuario
- **Éxito**: El usuario se puede registrar e ingresar en el sistema sin problema, con el 2FA para garantizar más seguridad.
- **Puntos valiosos**: Amazon Cognito para la autenticación y SNS para el envío del 2FA.

## 2. Integración de servicios y seguridad
- **Éxito**: El usuario puede enlazar su cuenta del servicio sin problema y puede realizar los pagos de forma segura.
- **Puntos valiosos**: Open Banking cumple los estándares de seguridad como PCI DSS, Cognito verifica información y la misma información se encuentra cifrada en PostgreSQL.

## 3. Sistema veloz
- **Éxito**: Las consultas y operaciones que se realizan duran menos de 2 segundos.
- **Puntos valiosos**: Redis como caché, AWS Lambda y API Gateway para una ejecución rápida sin servidores.

## 4. Asistencia con IA
- **Éxito**: Se recibe ayuda rápida y precisa, mediante un chatbot o voz.
- **Puntos valiosos**: Amazon Lex como IA que resolverá las dudas y guiará al usuario, y Amazon Polly que permite las respuestas por voz.

## 5. Notificaciones claras
- **Éxito**: El usuario recibe notificaciones SMS de pagos por realizar, pagos fallidos o información general.
- **Puntos valiosos**: Amazon SNS se encarga de enviar correctamente todo tipo de notificaciones necesarias (pagos, alertas, etc.).

## 6. Uptime y respaldo de información
- **Éxito**: La información está disponible y protegida en todo momento.
- **Puntos valiosos**: AWS Backup y RDS garantizan un respaldo de la base de datos y recuperación ante fallos, así como la alta disponibilidad del sistema.

## Link al diagrama
[Ver diagrama en Miro](https://miro.com/welcomeonboard/bUlTTCtKa2NxMjEvZVBocjMwc3Z3MTRQTGJwaVIzMURnN0xqa1pQaUZha1p2eTdkby9oUjlLSHhXRkVwMXlkdGN1Ry82bW1JS1FFZ01DcEpTTldZUHRWSkpRVGVPTy9VTTdNbEdSU3Y0UFdzUFFzVkx2UlJESzdCbWQrSEJ1K2FnbHpza3F6REdEcmNpNEFOMmJXWXBBPT0hdjE=?share_link_id=915577554788)

