FROM poet-typescript

RUN mkdir -p /app
WORKDIR /app

COPY ./package.json /app
COPY ./tsconfig.json /app

EXPOSE 3000
EXPOSE 5858

RUN npm install
CMD ["npm", "run", "start:watch"]