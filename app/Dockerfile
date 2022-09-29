FROM node:16.17.1 as build
WORKDIR /usr/local/app
COPY ./ /usr/local/app/
#RUN npm install -g yarn 
RUN yarn install    
RUN yarn build  
RUN yarn generate

FROM nginx:1.21.6-alpine
COPY --from=build /usr/local/app/dist  /usr/share/nginx/html
RUN rm -f /etc/nginx/conf.d/default.conf
COPY default.conf /etc/nginx/conf.d/default.conf
