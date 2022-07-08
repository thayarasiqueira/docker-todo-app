FROM node:14-alpine
EXPOSE 3001
ADD node_modules.tar.gz ./
COPY . home/node/app
CMD ["npm", "start"]