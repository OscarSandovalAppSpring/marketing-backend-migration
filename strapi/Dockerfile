FROM node:12.18.3-alpine
RUN mkdir -p /opt/app
WORKDIR /opt/a
COPY ./marketing-backend .
RUN yarn
EXPOSE 1337
CMD ["yarn", "develop"]