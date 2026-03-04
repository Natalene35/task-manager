FROM nginx:alpine

# Suppression config par défaut
RUN rm -rf /usr/share/nginx/html/*

# Copier fichiers statiques
COPY . /usr/share/nginx/html

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]