# /app
FROM node:19.2-alpine3.16

# cd app
WORKDIR /app

# esto copia los archivos app.js y pachage.json de mi proyecto a Dest /app en la imagen con el working directiory
# el cual corre con la distribución alpine de linux
COPY app.js package.json ./

# Instalar las dependencias
RUN npm install

# CMD = comando  
# Comando run de la imagen
CMD ["node", "app.js"]