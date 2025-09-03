# What dependency you want to use in your apps
FROM node

# In what directory docker should execute all the command
WORKDIR /app

# Where to copy files in host machine to the docker filesystem
COPY package.json /app

# Executing when images are being build
RUN npm install

COPY . /app

# In what port your apps will be exposed? but it doesn't do any damn thing, only documentation
EXPOSE 80

# Executed when images are being run
CMD ["node", "server.js"]