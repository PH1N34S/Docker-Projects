# Specify base image

FROM node:current-alpine3.10

# Specify Dependencies
WORKDIR /usr/app
COPY ./package.json /usr/app
RUN npm install
COPY ./ /usr/app
# Specify Startup command

CMD ["npm", "start"]