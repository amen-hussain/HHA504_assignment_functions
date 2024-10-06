# HHA504_assignment_functions
Exploring Serverless Computing and Cron Jobs in Azure, GCP, and GitHub

## Objective
The objective of this assignment is to introduce you to serverless computing and the use of cron jobs in cloud environments. You will deploy serverless functions on both Azure and Google Cloud Platform (GCP), and create a scheduled task using GitHub Actions.

## Instructions

### 1. Deploy a Serverless Function
- **Azure:**
  - Navigate to the Azure portal and create an Azure Function.

I first searched Function App within Microsoft Azure, then I selected create. From there I was prompted to choose a hosting plan (consumption.) In the Project details I set the configuration to python for runtime stack, 3.11 for version, East US for region, and Linux as the operating system. Third, I went to storage where I left settings on the default options. In Networking settings, I enabled public access. Next, I disabled application insights under monitoring. Furthermore, under the deployment tab, I enabled basic authentication and left the rest of the options as they were. Finally, I selected "review + create," confirmed the settings, and deployed the function which took approximately 1-2 minutes. 

<img width="1248" alt="image" src="https://github.com/user-attachments/assets/7b3b666d-0962-419d-8011-e8534de674cc">

  - Choose a simple trigger (e.g., HTTP trigger) and deploy a basic function (e.g., "Hello, World").

1. Go to resource. 
2. Create function in Azure portal. 

<img width="1247" alt="image" src="https://github.com/user-attachments/assets/a285cc5f-48c0-4588-b3fb-a39f1073daca">

<img width="1244" alt="image" src="https://github.com/user-attachments/assets/feaf65f6-d3d0-4c9f-8b2b-aca51f0d08dd">

<img width="1246" alt="image" src="https://github.com/user-attachments/assets/5bd12b53-5b41-4f15-a3d2-b4bd6456b561">

<img width="1244" alt="image" src="https://github.com/user-attachments/assets/e41bca74-f91b-4a99-8268-be61506058e0">

When I attempted to create my first serverless function "http_trigger1" an error popped up. I then deleted it, and created a new one, however another error popped up. To resolve this, I selected the refresh option with success.  

<img width="1242" alt="image" src="https://github.com/user-attachments/assets/f8748097-1056-44c4-9adb-bc85b6e80ccf">

<img width="1242" alt="image" src="https://github.com/user-attachments/assets/274d621f-b9c7-4ee0-a76e-98ed75553327">


- **GCP:**
  - Access the Google Cloud Console and create a Google Cloud Function.
  - Deploy a similar function with an HTTP trigger in GCP.

### 2. Create a Cron Job
- **GitHub Actions:**
  - Create a new GitHub repository (or use an existing one).
  - Set up a GitHub Action workflow that runs a script on a schedule (e.g., daily at midnight). You can use a simple script that logs "Scheduled task executed" to the console.

### 3. Explore Functions as a Service (FaaS)
- Reflect on the use cases for serverless functions in cloud environments. Consider the benefits and limitations of using Functions as a Service (FaaS) in both Azure and GCP.

### 4. Submit Your Work
- Create a Markdown document that includes:
  - Screenshots of the serverless function deployment process in both Azure and GCP.
  - The code and configuration of your GitHub Action workflow.
  - Screenshots or documentation of the GCP Cloud Scheduler setup.
  - A brief reflection on the use cases, benefits, and limitations of serverless functions.
- Commit and push this Markdown document, along with the screenshots and code, to your GitHub repository.

