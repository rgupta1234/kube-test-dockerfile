# Build your own docker image with command and code provided

# Dockerfile
Docker file for Kubernetes Test Application 

<h2> Docker Useful Commands </h2>
<p>
<code>docker build -t kube-test:v0.1 . </code><br>
<code>docker login</code><br>
<code>docker image tag kube-test:v0.1 **username**/kube-test:v0.1</code><br>
<code>docker push  **username**/kube-test:v0.1</code><br>
<code>docker run -d --name kube-test -p 8080:80 **username**/kube-test:v0.1</code><br>
</p>

## else you can pull my Docker image from
https://cloud.docker.com/repository/docker/bhargavshah86/kube-test
<br> 
<code>docker pull bhargavshah86/kube-test:v0.1</code>
