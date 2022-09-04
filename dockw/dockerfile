FROM node:16.17-alpine

COPY .  docsclone/
RUN ls
WORKDIR /docsclone/
RUN npm i
CMD ["npm", "devStart"]