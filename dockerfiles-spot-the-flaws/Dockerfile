FROM node:14-alpine

WORKDIR /app
COPY . ./
RUN npm install \
&& npm cache clean --force

EXPOSE 3000
CMD ["npm", "start"]



# FROM ubuntu

# ADD . /app

# RUN apt-get update
# RUN apt-get upgrade -y
# RUN DEBIAN_FRONTEND=noninteractive apt-get install -y npm nodejs
# RUN apt-get install -y openssh-server nginx
# RUN cd /app && npm install

# CMD sshd & cd /app && npm start
