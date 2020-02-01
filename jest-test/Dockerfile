FROM node:8.11.0
 
WORKDIR /usr/src/app
 
ADD . .
 
ENV TZ=America/Sao_Paulo 
 
RUN npm install
 
EXPOSE 8080
CMD ["node", "index.js"]