FROM node:21
WORKDIR /frontend
COPY package*.json ./
RUN npm ci
COPY . .

EXPOSE 5173

CMD ["npm","run","dev","--","--host"]
