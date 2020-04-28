FROM node:13

WORKDIR /app
COPY package.json /app
RUN npm install

COPY build.sh /app
ENTRYPOINT sh
CMD ./build.sh

#RUN npm run build
#RUN npx ng build

#CMD npx ng serve --host №0.0.0.0

#  --public-host http://localhost:8082/dip/api/webapps/view/REGULAR/f4DRXxi/j6iAgrViPiOvwEYR32mOK5COG4Lb5YTf/
# --base-href 
# --deploy-url asd
# --public-host http://localhost:8082/dip/api/webapps/view/REGULAR/f4DRXxi/j6iAgrViPiOvwEYR32mOK5COG4Lb5YTf/

#EXPOSE 4200
