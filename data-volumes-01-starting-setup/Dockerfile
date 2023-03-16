FROM node

WORKDIR /app

COPY package.json .


ARG DEFAULT_PORT=80

RUN npm install
 
COPY . .

ENV PORT 80

EXPOSE $PORT



CMD ["npm","start"]