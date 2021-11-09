FROM node:alpine
WORKDIR ./todo-app/back-end
ADD node_modules.tar.gz .
# COPY . .

# COPY --from=build /app/build /usr/share/nginx/html
EXPOSE 3001
ENTRYPOINT ["npm", "start"]
