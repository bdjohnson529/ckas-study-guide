# CKAS Study Guide
This guide contains different sections to study Kubernetes concepts. The guide is based on the Udemy course for CKAS certification.

## Section 1 - Core Concepts
Create pod
```bash
kubectl create -f section_1/pod-definition.yml
```

Create deployment
```bash
kubectl create -f section_1/deploy-definition.yml
```

Create replica set
```bash
kubectl create -f section_1/rc-definition.yml
```

## Section 2 - Configuration
Create Ubuntu sleeper Docker image
```bash
docker build -t section_2/ubuntu-sleeper
```

Create Ubuntu sleeper Pod
```bash
kubectl create -f section_2/pod-definition.yml
```