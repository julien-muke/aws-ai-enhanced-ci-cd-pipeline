# ![aws](https://github.com/julien-muke/Search-Engine-Website-using-AWS/assets/110755734/01cd6124-8014-4baa-a5fe-bd227844d263) AI-Powered CI/CD Pipeline for React Apps on AWS

<div align="center">

  <br />
    <a href="https://youtu.be/if5gMxb2LSM" target="_blank">
      <img src="https://github.com/user-attachments/assets/22475eca-5aa5-4961-b633-8cb1dda7d303" alt="Project Banner">
    </a>
  <br />

<h3 align="center">Build an AI-Powered CI/CD Pipeline on AWS using Amazon Inspector, Amazon Q and Amazon DevOps Guru.</h3>

   <div align="center">
     Build this hands-on demo step by step with my detailed tutorial on <a href="http://www.youtube.com/@julienmuke/videos" target="_blank"><b>Julien Muke</b></a> YouTube. Feel free to subscribe 🔔!
    </div>
</div>

## 🚨 Tutorial

This repository contains the steps corresponding to an in-depth tutorial available on my YouTube
channel, <a href="http://www.youtube.com/@julienmuke/videos" target="_blank"><b>Julien Muke</b></a>.

If you prefer visual learning, this is the perfect resource for you. Follow my tutorial to learn how to build projects
like these step-by-step in a beginner-friendly manner!

<a href="https://youtu.be/if5gMxb2LSM" target="_blank"><img src="https://github.com/sujatagunale/EasyRead/assets/151519281/1736fca5-a031-4854-8c09-bc110e3bc16d" /></a>

## <a name="introduction">🤖 Introduction</a>

Welcome! This repository contains the complete setup for AI-enhanced CI/CD pipeline built on Amazon Web Services.

We take a standard CI/CD pipeline for a React application and inject powerful AI capabilities at every stage, from writing the code to monitoring it in production. This project moves beyond legacy tools and embraces the future of DevOps with the latest services recommended by AWS.



## <a name="steps">🚀 Project Description & The "Why"</a>

In the world of cloud and DevOps, things move fast. Services that were standard yesterday are being replaced by more powerful, intelligent tools today. This project was born out of that evolution.

This repository reflects the new best practice, using the modern suite of AI developer tools:

- Amazon Q Developer: An AI coding assistant that lives in your IDE, helping you write higher-quality and more secure code before it's even committed.

- Amazon Inspector: An automated AI security service that scans your code and dependencies for vulnerabilities on every push, acting as a powerful security gate.

- Amazon DevOps Guru: An AIOps service that proactively monitors your live application, using machine learning to detect operational issues before they impact your users.

This project demonstrates how to build a CI/CD pipeline that doesn't just automate tasks but actively improves the quality and security of your software.



## <a name="steps">✨ Key Features</a>

- Fully Automated CI/CD: Push to GitHub, and the pipeline automatically builds and deploys your React app.

- AI-Powered Security Scanning: Amazon Inspector automatically scans every commit for vulnerabilities.

- Manual Approval Gate: A crucial checkpoint in the pipeline to review security findings before deployment.

- Shift-Left with AI Assistance: Integrates Amazon Q into the developer's local workflow for real-time code analysis and suggestions.

- Scalable Static Site Hosting: Deploys the React app to an Amazon S3 bucket configured for public website hosting.

- Proactive AI Monitoring: Amazon DevOps Guru watches your live application for anomalies and provides intelligent insights.

## <a name="steps">🛠️ How to Replicate This Project: Step-by-Step </a>

This project is built in two main parts. For a complete, beginner-friendly walkthrough, check out the full video tutorials on YouTube!

### Prerequisites: 

- An AWS Account
- A GitHub Account
- Node.js and npm installed
- A React application ready to be deployed
- VS Code (or another supported IDE) for the Amazon Q integration

### Part 1: Building the Foundational CI/CD Pipeline

This part covers setting up the core automation. We connect GitHub to AWS CodePipeline, which uses AWS CodeBuild to build our React app and deploy the static files to an S3 bucket.

👉 Watch the full tutorial for Part 1 on YouTube:
https://youtu.be/1k6s4shjpRc

### Part 2: Injecting AI for a Future-Proof Workflow

This is where we make the pipeline intelligent using the latest AI AWS services.

👉 Watch the full tutorial for Part 2 on YouTube:
https://youtu.be/1k6s4shjpRc

### Step-by-Step Summary:

- Enable Amazon Inspector: In the AWS Console, enable Inspector and connect it to your GitHub repository to start automated code scanning.

- Add a Security Gate: Modify your existing AWS CodePipeline to add a "Manual approval" stage after the source stage. This forces a review of Inspector's findings.

- Empower Your IDE with Amazon Q: Install the AWS Toolkit extension in your IDE (like VS Code) and sign in. Start using Amazon Q to get code suggestions, run on-demand security scans, and fix issues.

- Enable Proactive Monitoring: Set up Amazon DevOps Guru to monitor your AWS resources, specifically the S3 bucket where your application is hosted.

## ✅ Conclusion

By completing this project, you'll have more than just a deployment pipeline. You'll have a modern DevOps workflow that demonstrate the principles of DevSecOps and AIOps. This setup ensures that your application is not only delivered quickly but is also secure, reliable, and high-quality.

If you found this project helpful, please give it a ⭐ star on GitHub.

## 🚀 More

Follow my tutorial to learn how to build projects like these step-by-step in a beginner-friendly manner!

<a href="http://www.youtube.com/@julienmuke/videos" target="_blank">
      <img src="https://github.com/user-attachments/assets/a864c284-5647-4f4d-af70-386d7e0efadc" alt="Project Banner">
</a>