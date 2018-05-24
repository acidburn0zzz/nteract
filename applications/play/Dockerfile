FROM node:8@sha256:bba8a9c445fefc3e53fb2dfdfa755b0c119ae9f9999637e3b96ea37fae89d5d0
ADD . /playground
WORKDIR /playground
RUN npm install && npm run build

EXPOSE 3000

CMD ["/playground/node_modules/.bin/next", "start", "--host", "0.0.0.0"]
