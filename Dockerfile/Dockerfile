FROM node:17-alpine3.12


RUN mkdir -p /usr/src/nuxt-app
WORKDIR /usr/src/nuxt-app


RUN  yarn add next


COPY . /usr/src/nuxt-app/
RUN npm install


EXPOSE 3000

ENV NUXT_HOST=0.0.0.0
ENV NUXT_PORT=3000

CMD [ "npm", "start" ]