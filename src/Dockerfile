FROM nginx:1.19-alpine
COPY ./assets  /usr/share/nginx/html
RUN echo '<p>$ENVIRONMENT - $GITHUB_SHA</p>' >> /usr/share/nginx/html/index.html