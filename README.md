####Thanks to TrainwithSubham.
The application belongs to TrainwithSubham and im taking it for my demo project.

##### To start with the project #####

To begin first we need to select the best ec2 instance for our work and cost/hour , im choosing c6i.xlarge which provieds 4 cores and 8gb of Ram, Dont go for 2 core instances as they create issues with helm charts installation later.
We can use any home linux machine for this project too. ec2 not necessary.

###### Installations ####

1. Installing Kubectl (k8s folder)
2. Installing docker.
3. Installing kind
4. Spinning kind cluster using the config.yaml
5. Installing Helm.
6. Running the application .
7. Adding the Prometheus-community repo .
8. Installing Kube-prometheus-stack helm chart that contains prometheus,grafa,node-exporter and alert-manager.


####  Project Structure

1. The kind cluster folder contains commands for installing and spinning up kind cluster and nodes.
2. The k8s folder contains the deployment and services files .
3. Helm folder contains helm installation and adding the helm charts.
