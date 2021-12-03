FROM node:14.18

WORKDIR /app

COPY package.json /app/package.json
RUN npm install -g @angular/cli@13.0.4
RUN npm install

# add app
COPY . /app

# start app
CMD ng serve --host 0.0.0.0
