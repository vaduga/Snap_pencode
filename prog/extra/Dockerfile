FROM httpd:alpine
RUN apk add --update curl unzip zip && \
    rm -rf /var/cache/apk/*
RUN curl -o snap.zip "https://pencode.ru/Snap/snap.zip"
RUN rm -rf /usr/local/apache2/htdocs/index.html
RUN unzip snap.zip -d /usr/local/apache2/htdocs/
