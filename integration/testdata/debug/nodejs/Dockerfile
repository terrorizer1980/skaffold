FROM node:12.22.1-alpine3.10

WORKDIR /opt/backend
EXPOSE 3000
CMD ["node", "src/index.js"]

COPY . .
RUN npm install --no-package-lock
