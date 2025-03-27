FROM node:alpine

COPY package.json .

RUN npm install
RUN npm install --global gulp

WORKDIR /app

COPY . .

# required for docker desktop port mapping
EXPOSE 5173

CMD ["npm", "run", "react"]