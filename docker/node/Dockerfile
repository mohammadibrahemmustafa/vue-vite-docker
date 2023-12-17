FROM node:alpine

WORKDIR /srv/app

# Copy package.json and package-lock.json to the working directory
COPY package*.json ./

RUN npm install

# Copy the rest of the application files
COPY . .


EXPOSE 8000

CMD ["npm", "run", "dev"]