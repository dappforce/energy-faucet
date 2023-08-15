FROM node:14-alpine

WORKDIR /opt/subsocial

COPY . .

RUN yarn && \
    yarn prod

CMD [ "yarn", "start" ]
