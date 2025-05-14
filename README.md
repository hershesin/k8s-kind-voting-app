# k8s-kind-voting-app
A comprehensive guide for setting up a Kubernetes cluster using Kind on an AWS EC2 instance, installing and configuring Argo CD, and deploying applications using Argo CD.

<h1>Overview</h1>
This guide covers the steps to:
<ul>
<li>Launch an AWS EC2 instance.</li>
<li>Install Docker and Kind.</li>
<li>Create a Kubernetes cluster using Kind.</li>
<li>Install and access kubectl.</li>
<li>Set up the Kubernetes Dashboard.</li>
<li>Install and configure Argo CD.</li>
<li>Connect and manage your Kubernetes cluster with Argo CD.</li>
</ul>

<h1>Architecture</h1>
![k8s-kind-voting-app](https://github.com/user-attachments/assets/1eb7525f-30f4-478e-adbf-7c3c784d1fb7)


<h1>Observability</h1>
![prometheus](https://github.com/user-attachments/assets/fdae01d9-a42a-482a-97a3-c6ea6c3c1f0e)
![grafana](https://github.com/user-attachments/assets/f304ac87-e8d3-4bf5-acd7-6e8bd98757ba)


<ul>
<li>A front-end web app in Python which lets you vote between two options.</li>
<li>A Redis which collects new votes</li>
<li>A .NET worker which consumes votes and stores them in…</li>
<li>A Postgres database backed by a Docker volume</li>
<li>A Node.js web app which shows the results of the voting in real time</li>
</ul>
