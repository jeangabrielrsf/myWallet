FROM node

WORKDIR /src/usr

COPY . .

EXPOSE 5000

RUN npm i

# RUN mongod --dbpath ~/.mongo

CMD ["npm", "start"]