FROM node:16-buster
ARG REACT_APP_API_URL
ENV REACT_APP_API_URL=$REACT_APP_API_URL
WORKDIR /app
COPY /client/package.json ./
COPY /client/package-lock.json ./
RUN npm install
COPY ./client .
EXPOSE 5173
CMD ["npm","run", "build"]
CMD ["npm","run", "dev"]