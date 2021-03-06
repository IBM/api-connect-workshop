# Create, deploy and test APIs using API Connect 
[IBM® API Connect](https://www.ibm.com/cloud/api-connect)
 is a complete, intuitive and scalable API platform that lets developers create, expose, manage and monetize APIs across clouds.

<p align="left">
<img width="75%" height="75%" src="./images/img1.png">
</p>

IBM API Connect on IBM Cloud provides a unified user experience across the API lifecycle and helps you to create and manage your APIs with business-level controls by setting different levels of security and visibility while sharing APIs with application developers. (You can also use IBM API Connect that is included in IBM Cloud Pak for Integration to manage your APIs.)

In this [lab](https://github.com/IBM/api-connect-workshop/blob/main/lab.md) you will create a new API using the OpenAPI definition of an existing RESTful web-service that gets realtime stock quotes. You will then test the API by deploying it in the Developer Portal. The app uses the API definition that you will create to get realtime stock quotes.

## Getting Started: 
In this workshop we will get you started with creating a Lite API Connect Service on IBM Cloud 

### Prerequisites
Register and create an [IBM Cloud Account](https://ibm.biz/ibm-tcs-workshop) 

## Setting up API Connect Service 

### Step 1: 
Go to [IBM Cloud Catalog](https://cloud.ibm.com/catalog) and search for API Connect.
![](./images/img2.png)

### Step 2: 
Select `Lite` Plan and give your service a name. Click on the `Create` Button to create your Lite service
![](./images/img3.png)

### Step 3: 
On the IBM Cloud Dashboard, in the Cloud Foundry Services list, click the API Connect service instance. The API Connect dashboard is displayed.
![](./images/img4.png)

## Lab 
Now that we have our service set up we can move on to the lab

- [Lab: Create, deploy and test a new API using the API Connect Developer Toolkit](https://github.com/IBM/api-connect-workshop/blob/main/lab.md)

