#Base image
FROM node:lts

# Set the working directory
WORKDIR /app

# Copy the package.json
COPY package.json .

# install project dependencies
RUN yarn install

# Copy the package.json
COPY . .

# Expose a port
EXPOSE 3000

# Executables
CMD [ "yarn", "dev" ]
