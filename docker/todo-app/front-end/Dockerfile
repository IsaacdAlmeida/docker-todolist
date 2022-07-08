FROM node:14-alpine
#WORKDIR NEEDED
WORKDIR /app
COPY . .
ADD node_modules.tar.gz .
EXPOSE 3000
RUN npm install
CMD [ "npm", "start" ]
