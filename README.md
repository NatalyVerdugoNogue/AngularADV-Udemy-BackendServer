# Backend-Server

Este es el código necesario para establecer el backend conectado a MongoDB usando Mongoose.

Para ejecuarlo, es necesario reconstituir los módulos de node usando el comando

```
npm install
```

### Carpeta Config

Para el funcionamiento ademas es necesario crear una carpeta en la raiz del proyecto con el nombre config con un archivo *config.js* con el siguiente formato

```
module.exports.SEED = '<SEED>';

module.exports.GOOGLE_CLIENT_ID = '<client_id>';
module.exports.GOOGLE_SECRET = '<client_secret>';
```

Donde se detallan las claves secretas del proyecto en Google

## Dentro de Google-SingIn-demo

Existe un pequeño ejercicio para probar la autentificacion de Google en un Front-End básico pero funcional.
