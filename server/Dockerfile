#Base image
FROM node:lts

# Set the working directory
WORKDIR /server

# Copy the package.json
COPY package.json .

# install project dependencies
RUN yarn install

# Copy the package.json
COPY . .

# Expose container to a port
EXPOSE 3001

# Executables
CMD [ "yarn", "start" ]
