FROM node:0.12.0
RUN apt-get update -qq && apt-get install -y build-essential
RUN apt-get install -y ruby
# RUN gem install sass
RUN mkdir /src
RUN npm install gulp webpack -g

#RUN curl -Lk 'https://api.equinox.io/1/Applications/ap_pJSFC5wQYkAyI0FIVwKYs9h1hW/Updates/Asset/ngrok.zip?os=linux&arch=amd64&channel=stable' > ngrok.zip
#RUN unzip ngrok.zip -d /bin && rm -f ngrok.zip

WORKDIR /src
#ADD ./package.json /src/package.json
#RUN npm install
EXPOSE 3000
EXPOSE 35729
#CMD ["npm", "start"]
