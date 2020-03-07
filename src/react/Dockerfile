FROM ubuntu:18.04

RUN apt-get update && apt-get upgrade -y
RUN apt-get install curl -y
RUN curl -sL https://deb.nodesource.com/setup_13.x | bash
RUN apt-get install -y nodejs
RUN node -v
RUN npm -v
RUN npx create-react-app my-app
WORKDIR "/my-app"
CMD ["npm", "start"]