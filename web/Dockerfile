FROM node:alpine
WORKDIR /evook_web
EXPOSE 5173

# Assuming package.json is accessable via volume
CMD npm install; npx nodemon --watch package.json --exec "npm install" & npm run dev;