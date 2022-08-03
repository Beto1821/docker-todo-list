FROM mjgargani/puppeteer:trybe1.0
WORKDIR /usr/app
COPY . .
ADD ./node_modules.tar.gz ./node_modules
RUN ["npm", "install"]
CMD [ "npm", "test" ]
