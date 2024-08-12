FROM node:16-buster
WORKDIR /app
COPY /server/package.json ./
COPY /server/package-lock.json ./
RUN npm install
COPY ./server .
EXPOSE 3001
CMD ["npm","start"]