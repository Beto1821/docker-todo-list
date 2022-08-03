FROM node:14
WORKDIR /usr/app
COPY . .
ADD ./node_modules.tar.gz ./node_modules
RUN ["npm", "install"]
EXPOSE 3001
CMD [ "npm", "start" ]
