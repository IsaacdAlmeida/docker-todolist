FROM node:14-alpine
#WORKDIR NEEDED
WORKDIR /app
COPY . .
ADD node_modules.tar.gz .
EXPOSE 3001
RUN npm install
CMD [ "npm", "start" ]