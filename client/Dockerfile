FROM node:16-buster
WORKDIR /app
COPY /client/package.json ./
COPY /client/package-lock.json ./
RUN npm install
COPY ./client .
EXPOSE 5173
CMD ["npm","run", "build"]
CMD ["npm","run", "dev"]