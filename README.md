# app_flask
Esta api es para el desafio de tripulaciones que consiste en una app para el colegio de administradores de fincas de Valencia y Castellon. La api lleva la siguiente estructura:
1- Recepcion de pdfque sube el usuario en la app, esto entra en nuestra api a traver de un endppoint dado por fullstack
2- Transformacion de pdf a texto.
3- Resumen del texto y post del mismo a BBDD tipo mongoDB
4- Generacion de audio a partir de resumen y post a BBDD tipo mongoDB