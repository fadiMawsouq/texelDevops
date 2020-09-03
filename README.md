# texelDevops



# docker actions
- build : docker build -t fadizaboura/nginxapp:1.5 .
- run local image : docker run -it -d -p 5000:5000 --name webapp fadizaboura/nginxapp:1.5
- tag : docker tag fadizaboura/nginxapp:1.5 fadizaboura/nginxapp:latest
- push : docker push fadizaboura/nginxapp:latest

# References
- http://pjdietz.com/2016/08/28/nginx-in-docker-without-root.html
- https://www.rockyourcode.com/run-docker-nginx-as-non-root-user/