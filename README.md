# Cloud Services Models

## Introduction
In this project, I explored cloud service models, specifically **IaaS**, **PaaS**, and **SaaS**, and successfully set up a managed service using **AWS Elastic Beanstalk**. The goal was to understand the differences between these models and gain hands-on experience with a cloud service platform.

## Examples of IaaS, PaaS, and SaaS

### IaaS (Infrastructure as a Service)
- **AWS EC2**: Virtual machines for running applications.
- **Google Compute Engine**: Google Cloud's IaaS offering.

### PaaS (Platform as a Service)
- **AWS Elastic Beanstalk**: Managed service for deploying web applications.
- **Google App Engine**: Managed platform for developing and deploying apps.

### SaaS (Software as a Service)
- **Google Workspace**: Cloud-based productivity tools.
- **Slack**: Cloud-based team communication platform.

---

## Research on AWS and GCP Offerings

### AWS (Amazon Web Services)
- **Elastic Beanstalk**: Managed service for deploying applications without managing infrastructure.
- **EC2**: Scalable virtual machines for running applications.
- **S3**: Object storage for storing and managing data.
- **Lambda**: Serverless compute service for event-driven applications.

### GCP (Google Cloud Platform)
- **App Engine**: Managed PaaS for deploying apps.
- **Compute Engine**: Scalable virtual machines for running applications.
- **Cloud Functions**: Serverless compute for event-driven code execution.
- **BigQuery**: Managed data warehouse for analytics.

---

## Managed Service Setup (AWS Elastic Beanstalk)

In this section, I will walk through the steps I followed to set up a simple Node.js application using **AWS Elastic Beanstalk**.

### Step-by-Step Guide to Set Up Elastic Beanstalk:

1. **Create an Application**:
    - Logged into the AWS Management Console and navigated to **Elastic Beanstalk**.
    - Created a new application and named it `my-m4ace-sample-app`.

2. **Choose a Platform**:
    - Selected **Python** as the platform for my web application.

3. **Configure Environment**:
    - Choose the default **Web Server Environment** and skipped advanced configurations for simplicity.

4. **Deploy and Launch**:
    - After reviewing the configurations, I clicked **Create Environment**, and Elastic Beanstalk automatically provisioned the environment and deployed the app.

5. **Access the Application**:
    - Once the environment was ready, I accessed the application using the URL provided: `http://my-m4ace-sample-app-dev.eba-zn5mmnkw.us-east-1.elasticbeanstalk.com/`.

### Screenshots

Here are the key screenshots showing the steps of setting up Elastic Beanstalk:

- **Screenshot 1**: Elastic Beanstalk Dashboard
  ![Elastic Beanstalk Dashboard](https://raw.githubusercontent.com/OrireB/cloud-services-models/7239ee35bdab1c025bfda31330819e385df61455/Screenshot%20(69).png)

- **Screenshot 2**: Platform Selection Screen
  ![Platform Selection](https://raw.githubusercontent.com/OrireB/cloud-services-models/7239ee35bdab1c025bfda31330819e385df61455/Screenshot%20(70).png)

- **Screenshot 3**: Configure Environment
  ![Configure Environment](https://raw.githubusercontent.com/OrireB/cloud-services-models/7239ee35bdab1c025bfda31330819e385df61455/Screenshot%20(73).png)

- **Screenshot 4**: Accessing the Deployed Application
  ![Deployed Application](https://raw.githubusercontent.com/OrireB/cloud-services-models/7239ee35bdab1c025bfda31330819e385df61455/Screenshot%20(79).png)

---

## Conclusion

Through this project, I explored the **IaaS**, **PaaS**, and **SaaS** models, compared offerings from **AWS** and **GCP**, and successfully deployed a Node.js application using **AWS Elastic Beanstalk**. This process helped me understand the ease of deploying applications on managed platforms like Elastic Beanstalk and the importance of choosing the right cloud service model depending on project requirements.

---
