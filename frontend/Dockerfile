FROM node:12
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
COPY package.json /usr/src/app/
COPY package-lock.json /usr/src/app/
EXPOSE 3000
RUN npm install
COPY . /usr/src/app
CMD npm start