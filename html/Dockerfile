from node:18
workdir /app
copy package.json /app
run npm install 
copy . /app
cmd node server.js
expose 2000
