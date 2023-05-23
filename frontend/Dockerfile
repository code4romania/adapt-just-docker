# Image
FROM node:18

# Set up work directory
WORKDIR /var/www/adapt-just-front

# Configure port
ENV HOST 0.0.0.0

EXPOSE 3000

# Init command
CMD ["sh", "-c", "yarn install && yarn run dev"]
