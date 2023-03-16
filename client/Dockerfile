#Base image
FROM node:lts

# Set the working directory
WORKDIR /app

# Copy the package.json
COPY ./package.json /app/package.json

# install project dependencies
RUN npm install

# Expose a port
EXPOSE 3000

# Executables
CMD [ "yarn", "dev" ]
