FROM node:18

WORKDIR /app

COPY . .
# RUN mkdir src

RUN rm -rf node_modules
RUN yarn install

EXPOSE 3000

CMD ["yarn", "dev", "-o"]