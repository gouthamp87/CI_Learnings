# What base image to use
FROM node:alpine

#specifiy a source folder

WORKDIR /src/apps

#Copy the JSON first

COPY package.json .

#Install the NPM first

RUN npm install

#Copy the remaining source files

COPY . .

# Now run the command

CMD ["npm", "start"]


