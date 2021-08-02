# Create a project on docker-compose and convert to yaml kubernetes
<h2>Intro</h2>
<p>We will create a docker-compose for development environment and after we will convert for yaml files for create a pods and services on kubernetes for production environment</p>

<h2>1 - Create a Docker-compose file:</h2> 
<p>1- bridge network on docker</p>
<p>2- mongo db</p>
<p>3- web application will pull image "erikdelimavicente/rotten-potatoes:v1"</p>

<h2>Commands for create Web Applicantion at local environment (development environment)?</h2>
<p>execute this command: "docker-compose up -d"
<p>After, open your browser and type "localhost:8080"</p>

<h2>Command for destroy Web Applicantion at local environment (development environment)?</h2>
<p>execute this command: "docker-compose down"</p>

<h2>2 - Create yaml files to k8s pods</h2>
<p>1- Create yaml for mongo db and service</p>
<p>2- Create yaml for app and service</p>

<h2>Commands for create product environment on k8s<h2>
<p>kubectl create -f mongo.yaml</p>
<p>kubectl create -f web.yaml</p>
<p>open on browser this url "0.0.0.0:5000"</p>
