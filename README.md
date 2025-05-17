<h1><b>Kind Voting App</b></h1>
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

![k8s-kind-voting-app](https://github.com/user-attachments/assets/abad637e-c59a-4e6f-8638-30258278e1a3)


<h1>Observability</h1>

![grafana](https://github.com/user-attachments/assets/d33a47c8-a2ab-420f-8f46-6f6c450ca881)

![prometheus](https://github.com/user-attachments/assets/0f0b30e9-25c4-43c6-af32-9df7f2999c3a)


<ul>
<li>A front-end web app in Python which lets you vote between two options.</li>
<li>A Redis which collects new votes</li>
<li>A .NET worker which consumes votes and stores them in…</li>
<li>A Postgres database backed by a Docker volume</li>
<li>A Node.js web app which shows the results of the voting in real time</li>
</ul>
