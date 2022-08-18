FROM node:16

EXPOSE 1337

COPY . /app

WORKDIR /app

RUN npm install

#RUN npx browserslist@latest --update-db

RUN npm run build

CMD ["npm", "start"]
