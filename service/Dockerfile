FROM node:alpine
WORKDIR /evook_service
EXPOSE 3000

# Assuming package.json is accessable via volume
CMD npm install nodemon; npx nodemon --watch package.json --exec "npm install" & npm start;