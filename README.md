# dockerfile
Docker file for Kubernetes Test Application 
<h3> Docker Useful Commands <h3>
<p>
<code>docker build -t kube-test:v0.1 . </code><br>
<code>docker login</code><br>
<code>docker image tag kube-test:v0.1 **username**/kube-test:v0.1</code><br>
<code>docker push  **username**/kube-test:v0.1</code><br>
<code>docker run -d --name kube-test -p 8080:80 **username**/kube-test:v0.1</code><br>
</p>
