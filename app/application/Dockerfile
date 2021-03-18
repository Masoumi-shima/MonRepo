FROM node:12-alpine
WORKDIR /app/application
COPY . .
RUN yarn install --production
CMD ["node", "/app/application/src/index.js"]
