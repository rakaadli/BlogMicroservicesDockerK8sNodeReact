FROM node:alpine
 
# Tambah ini supaya bisa jalan create-react-appnya
ENV CI=true
 
WORKDIR /app
COPY package.json ./
RUN npm install
COPY ./ ./
 
CMD ["npm", "start"]