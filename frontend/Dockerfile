FROM node:19-alpine3.15
WORKDIR /frontend
COPY package*.json ./
RUN npm install
COPY . .
RUN npm run build
EXPOSE 3000
CMD ["npx", "serve", "build"]