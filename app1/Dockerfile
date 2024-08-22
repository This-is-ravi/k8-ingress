FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
RUN echo "<h1>Hello, I am from APP-1</h1>" > /usr/share/nginx/html/index.html

#to deploy this nginx app in k8s, we need resource like deployment,pod defi,service,ingress controller
#in manifest files