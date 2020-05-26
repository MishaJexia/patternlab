FROM node:14.0.0
WORKDIR /app
COPY . .
RUN npm install
RUN npm run pl:build
ENTRYPOINT npm run pl:serve
