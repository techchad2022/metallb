```php
CONTENTS OF THIS FILE
---------------------
 * Introduction
 * Requirements
 * Recommended modules
 * Installation
 * Configuration
 * Troubleshooting
 * FAQ
 * Maintainers
```
# Metallb
The Kubernetes clusters deployed in cloud environments use the functionality from the provider to dynamically provision managed load balancers for the services of type LoadBalancer. MetalLB implements the load balancer functionality for local or bare metal Kubernetes clusters that are not deployed in cloud environments.

## Installation
Clone the git repo and change directory to the parent folder.
```bash
git clone https://github.com/techchad2022/metallb.git
cd metallb
```
Apply metallb-native.yaml
```bash
kubectl apply -f metallb-native.yaml
```



## Configuration
Apply address pool located in values.yml
```bash
kubectl apply -f values.yml
```
Apply layer 2 Advertisement present in l2.yml
```bash
kubectl apply -f values.yaml
```
Done. Enjoy
# Author
name: techchad2022
email: techchad2022@gmail.com
