FROM node:14-alpine
EXPOSE 3000
WORKDIR .todo-app/front-end/
COPY . .
RUN npm install
ADD node_modules.tar.gz ./
CMD ["npm", "start"]