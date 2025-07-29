FROM node:24-alpine

# where you want your work to be done
WORKDIR /app

# Copy the package.json into the root folder
COPY package.json .

# Install all the dependency
RUN npm install

# Copy the following packages to my working directory
COPY . .

EXPOSE 3000

CMD ["npm", "start"]
