FROM node:19-alpine3.15
WORKDIR /frontend
COPY . .
RUN npm i
RUN npm run build
ENV NODE_ENV production
EXPOSE 3000
CMD ["npx", "serve", "build"]