ARG NODE_VERSION
FROM node:$NODE_VERSION
# install sass
RUN npm install -g sass
# ENTRYPOINT (Default Command to Execute at Runtime)
# Necesito que se ejecute esto:
#  Y poder especificar primer y segundo parametro
# sass --watch scss/:css/
ENTRYPOINT ["sass", "--watch", "/scss:/css"]