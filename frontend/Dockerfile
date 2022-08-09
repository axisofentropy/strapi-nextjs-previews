FROM node:14

EXPOSE 3000

COPY . /app

WORKDIR /app

RUN npm install

RUN npx browserslist@latest --update-db

CMD ["npm", "run", "dev"]
