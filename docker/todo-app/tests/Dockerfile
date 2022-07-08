FROM mjgargani/puppeteer:trybe1.0
EXPOSE 3000
WORKDIR /home/mjgargani/app
ADD node_modules.tar.gz ./
COPY . home/mjgargani/app
CMD ["npm", "test"]