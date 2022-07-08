FROM node:14-alpine
#WORKDIR NEEDED
WORKDIR /app
COPY . .
COPY node_modules.tar.gz .
EXPOSE 3001
RUN npm install
CMD [ "npm", "start" ]