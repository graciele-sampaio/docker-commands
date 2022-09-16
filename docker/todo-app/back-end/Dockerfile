FROM node:14-alpine
EXPOSE 3001
WORKDIR todo-app/back-end/
COPY . .
RUN npm install
ADD node_modules.tar.gz ./
CMD ["npm", "start"]
