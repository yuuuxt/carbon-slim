ARG carbon_version=4.8.1

FROM node:12

WORKDIR /app

RUN git clone https://github.com/carbon-app/carbon.git --branch ${carbon_version}
WORKDIR /app/carbon
RUN yarn install
RUN yarn build
EXPOSE 3000
CMD [ "yarn", "start" ] 