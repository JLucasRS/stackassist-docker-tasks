FROM node
COPY . /backend
WORKDIR /backend
RUN npm install

# Running 'docker save -o task1.tar task1_web' would create and exportable image 
# but the file was > 900 mb and github couldn't handle it,