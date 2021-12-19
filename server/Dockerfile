FROM node:16-alpine
#dir for app in docker env
WORKDIR /app
#copy package.json to app
COPY package.json .
#to add all deps
RUN npm install
#copy others files in project
COPY . .
#conrainer runned on port 5000
EXPOSE 5000
#run app
CMD ["npm", "run", "serve"]