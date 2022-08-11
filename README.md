# K8s Test

This repo contains kubernetes yaml files for a deployment and service.
These files contain some misconfigurations that will prevent the pod from running.

The objective of this test is to do what ever it takes to get the nginx server to run without restarts.

Follow the steps below to get started

# Lab

## Step 1: Login to Killercoda

Login to [https://killercoda.com/login](https://killercoda.com/login)

## Step 2: Start a kubernetes lab

- When logged in, select the **Kubernetes** card under the **Features** section.
- Select **A Playground** card.

## Step 3: Checkout the code

- Wait for `controlplane $` to show on the browser based terminal
- Clone the repository on the terminal by running the following command
 `git clone https://github.com/princekaguda/k8s-test.git`

## Step 4: Deploy the app

- Change directory into the cloned repo using the following command `cd k8s-test`
- Deploy the app by running 
`kubectl apply -f specs/`
- Make whatever changes you need to get the app running