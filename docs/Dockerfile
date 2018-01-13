FROM dalongrong/node-yarn
RUN mkdir -p /home/nodejs/app
WORKDIR /home/nodejs/app
COPY docs /home/nodejs/app
RUN yarn add live-server
CMD ["live-server"]