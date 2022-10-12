# ImageStore

ImageStore is a self-hosted photo gallery, that makes Google Photos users feel right at home.

## Features:
- Clean and intuitive UI for desktop and mobile browsers
- Automatic thumbnail creation for faster loading times
- Fast uploads for both photos and videos
- Albums to sort your photos
- Easily searchable labels
- Automatic image-tagging
- Face recognition
- AI based search
- Modular architecture for easy expanding

[Online demo](https://gregordr.github.io/ImageStore/)

## Introduction
Imagine you are working for a software development company that has the need of
developing, testing, assuring the quality and shipping to production an application that
comprises at least a backend service and a frontend web application.
Developers then need a way of:

- running the application locally (with docker and docker compose)
- executing unit and feature tests on the code automatically (on a CI environment)
- deploy the application on the QA environment (a Kubernetes cluster)
- finally ship it to production on a cloud service (AWS, GCP, Azure…)


## Getting Started
1. Clone this repository

2. Running the application locally with docker-compose

3. Bring the application into a kubernetes cluster

4. Run a CI service in the cluster



## Dependencies
1. Install  latest version [Docker](https://docs.docker.com/get-docker/)
2. Install  latest version  [Dokcer-compose](https://docs.docker.com/compose/install/)
3. Install  latest version [Minikube](https://minikube.sigs.k8s.io/docs/start/)
4. Install latest version [Terraform](https://www.terraform.io/downloads.html)

## Instructions
Once you've gathered your dependencies, we'll need the following steps to deploy the scalable web server on Azure:
1. Deploy the packer image
2. Deploy the infrastructure with Terraform template
