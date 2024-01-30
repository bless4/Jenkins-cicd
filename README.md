# Jenkins-CICD (TechLab)

It's 24-hours hands-on instructor-led training program covers Jenkins and CI/CD concepts, with topics distributed across 9 lessons. This GitHub repository contains all the hands-on lab materials on different branches.


## INDEX:

1. [How to Use this Repository and Branches](#how-to-use-this-repository-and-branches)
2. [Repository Structure](#repository-structure)
3. [Branch Name - Hands-on Lab](#branch-name-hands-on-lab)
4. [Full Course Outline](#full-course-outline)
5. [References](#references)
6. [Disclaimer](#disclaimer)

## Course Outline

- Lesson 1: Course Introduction
- Lesson 2: Introduction to CI/CD
- Lesson 3: Getting Started With Jenkins
- Lesson 4: Build Jobs and Configurations
- Lesson 5: Configuring Build Pipelines
- Lesson 6: Automated Testing In Jenkins
- Lesson 7: Code Quality Improvement using Jenkins
- Lesson 8: Automated Deployment and Continuous Delivery
- Lesson 9: Distributed System In Jenkins
- Course-end project
- QnA

For detailed information on each lesson, see the full course outline below.

## How to Use this Repository and Branches

To use this repository, you need to fork it and make sure to enable the "Include all branches" option. Follow these steps:

1. Navigate to the repository:  [Jenkins-cicd](https://github.com/manikcloud/Jenkins-cicd/tree/main)
2. In the top-right corner of the page, click the "Fork" button.
3. A dialog box will appear, asking you to select the account where you want to fork the repository. Choose your desired account.
4. In the "Include all branches" section of the dialog box, make sure to check the box next to "Include all branches."
5. Click "Fork repository" to create a copy of the repository with all the branches included in your account.
6. Now, you have successfully forked the repository with all its branches. You can now use the different branches for various learning purposes.

To switch between branches in your forked repository, follow these steps:

1. Go to your forked repository on GitHub.
2. Click on the "Branch" dropdown button, which is located in the top-left corner of the page, under the repository name.
3. In the dropdown menu, you'll see a list of all the available branches. Click on the desired branch to switch to it.

With this guide, you should be able to use the repository and its branches effectively. 

`Happy learning!`

## Repository Structure

Each branch in the Jenkins-CICD Simplilearn tutorial can have its own README file with step-by-step instructions for completing the hands-on exercises.


This repository contains hands-on lab materials on different branches:

| Sl. No. | Branch Name             | Details                                   | Link                                                                                             |
|---------|-------------------------|-------------------------------------------|--------------------------------------------------------------------------------------------------|
| 1       | main                    | Main branch                               | [main](https://github.com/manikcloud/Jenkins-cicd/tree/main)                                     |
| 2       | 0.1_create_ec2_tf       | Create EC2 instances with Terraform      | [0.1_create_ec2_tf](https://github.com/manikcloud/Jenkins-cicd/tree/0.1_create_ec2_tf)           |
| 3       | 0.2_ansible_install_jenkins | Install Jenkins using Ansible         | [0.2_ansible_install_jenkins](https://github.com/manikcloud/Jenkins-cicd/tree/0.2_ansible_install_jenkins) |
| 4       | 3.1-free-style          | Free-style Jenkins job                   | [3.1-free-style](https://github.com/manikcloud/Jenkins-cicd/tree/3.1-free-style)                 |
| 5       | 3.1.1-maven-style       | Maven-style Jenkins job                  | [3.1.1-maven-style](https://github.com/manikcloud/Jenkins-cicd/tree/3.1.1-maven-style)           |
| 6       | 3.1.2-free-style        | Another free-style Jenkins job           | [3.1.2-free-style](https://github.com/manikcloud/Jenkins-cicd/tree/3.1.2-free-style)             |
| 7       | 4.4_email_notification  | Email notification configuration         | [4.4_email_notification](https://github.com/manikcloud/Jenkins-cicd/tree/4.4_email_notification) |
| 8       | 4.5-gradle              | Gradle build job                         | [4.5-gradle](https://github.com/manikcloud/Jenkins-cicd/tree/4.5-gradle)                         |
| 9       | 4.6_string_parameter    | String parameter example                 | [4.6_string_parameter](https://github.com/manikcloud/Jenkins-cicd/tree/4.6_string_parameter)     |
| 10      | 4.7_tag_parameter       | Tag parameter example                    | [4.7_tag_parameter](https://github.com/manikcloud/Jenkins-cicd/tree/4.7_tag_parameter)           |
| 11      | 4.8_remote_trigger      | Remote trigger configuration             | [4.8_remote_trigger](https://github.com/manikcloud/Jenkins-cicd/tree/4.8_remote_trigger)         |
| 12      | 4.9_enabling_security   | Enabling security in Jenkins             | [4.9_enabling_security](https://github.com/manikcloud/Jenkins-cicd/tree/4.9_enabling_security)   |
| 13      | 5.1-helloworld-pipeline | Hello World pipeline example             | [5.1-helloworld-pipeline](https://github.com/manikcloud/Jenkins-cicd/tree/5.1-helloworld-pipeline) |
| 14      | 5.2-pipeline-no-jenkinsfile | Pipeline without Jenkinsfile          | [5.2-pipeline-no-jenkinsfile](https://github.com/manikcloud/Jenkins-cicd/tree/5.2-pipeline-no-jenkinsfile) |
| 15      | 5.3-maven-jenkinsfile-pipeline | Maven Jenkinsfile pipeline            | [5.3-maven-jenkinsfile-pipeline](https://github.com/manikcloud/Jenkins-cicd/tree/5.3-maven-jenkinsfile-pipeline) |
| 16      | 5.4-snippet-generator   | Snippet generator usage                 | [5.4-snippet-generator](https://github.com/manikcloud/Jenkins-cicd/tree/5.4-snippet-generator)     |
| 17      | 5.5_restarting_pipeline | Restarting a pipeline                   | [5.5_restarting_pipeline](https://github.com/manikcloud/Jenkins-cicd/tree/5.5_restarting_pipeline) |
| 18      | 6.01-junit-maven        | JUnit with Maven                        | [6.01-junit-maven](https://github.com/manikcloud/Jenkins-cicd/tree/6.01-junit-maven)               |
| 19      | 6.02-jacoco             | Jacoco code coverage                    | [6.02-jacoco](https://github.com/manikcloud/Jenkins-cicd/tree/6.02-jacoco)                         |
| 20      | 6.03-Jacoco-pipeline-job| Jacoco pipeline job                     | [6.03-Jacoco-pipeline-job](https://github.com/manikcloud/Jenkins-cicd/tree/6.03-Jacoco-pipeline-job)|
| 21      | 6.03-JacocoPublisher    | Jacoco Publisher plugin                 | [6.03-JacocoPublisher](https://github.com/manikcloud/Jenkins-cicd/tree/6.03-JacocoPublisher)       |
| 22      | 6.04-Clover             | Clover code coverage                     | [6.04-Clover](https://github.com/manikcloud/Jenkins-cicd/tree/6.04-Clover)                         |
| 23      | 7.0-sonarqube-lab       | SonarQube lab setup                     | [7.0-sonarqube-lab](https://github.com/manikcloud/Jenkins-cicd/tree/7.0-sonarqube-lab)             |
| 24      | 7.1-sonarqube-ec2       | SonarQube on EC2                        | [7.1-sonarqube-ec2](https://github.com/manikcloud/Jenkins-cicd/tree/7.1-sonarqube-ec2)             |
| 25      | 7.3-sonarcube-docker    | SonarQube with Docker                   | [7.3-sonarcube-docker](https://github.com/manikcloud/Jenkins-cicd/tree/7.3-sonarcube-docker)       |
| 26      | 7.4-findbug-pmd-checkstyle | FindBugs, PMD, and Checkstyle         | [7.4-findbug-pmd-checkstyle](https://github.com/manikcloud/Jenkins-cicd/tree/7.4-findbug-pmd-checkstyle) |
| 27      | 7.5complexity-scatter-plot | Complexity scatter plot analysis      | [7.5complexity-scatter-plot](https://github.com/manikcloud/Jenkins-cicd/tree/7.5complexity-scatter-plot) |
| 28      | 8.1-addressbook         | Address book project                     | [8.1-addressbook](https://github.com/manikcloud/Jenkins-cicd/tree/8.1-addressbook)                 |
| 29      | 8.2-python-flask-app    | Python Flask application                 | [8.2-python-flask-app](https://github.com/manikcloud/Jenkins-cicd/tree/8.2-python-flask-app)       |
| 30      | 8.3-php-docker          | PHP application with Docker              | [8.3-php-docker](https://github.com/manikcloud/Jenkins-cicd/tree/8.3-php-docker)                   |
| 31      | 9.1-master-slave        | Master-slave Jenkins setup               | [9.1-master-slave](https://github.com/manikcloud/Jenkins-cicd/tree/9.1-master-slave)               |
| 32      | 9.2-final-project       | Final project                            | [9.2-final-project](https://github.com/manikcloud/Jenkins-cicd/tree/9.2-final-project)             |


GitHub repository: [https://github.com/manikcloud/Jenkins-cicd.git](https://github.com/manikcloud/Jenkins-cicd.git)


Here's a template you can use as a starting point for each branch's README file:
## Branch Name - Hands-on Lab

### Overview

Provide a brief overview of the hands-on exercise and its objectives.

### Prerequisites

List any prerequisites for the exercise, including software installations, system configurations, or prior knowledge.

### Step-by-Step Instructions

1. **Step 1:** Describe the first step in the exercise.
2. **Step 2:** Describe the second step in the exercise.
3. **Step 3:** Describe the third step in the exercise.
4. ...

-----------------------------------------------------------------------------------------------------------
## Full Course Outline

<details>
<summary>Click to expand the full course outline</summary>

## Lesson 1: Course Introduction
- Course Objectives
- Course Outline
- Prerequisites of this course
- Highlights of this course

## Lesson 2: Introduction to CI/CD

By the end of this lesson, you will be able to explain:

- Traditional Software Development
- Continuous Integration
- Continuous Delivery
- Continuous Deployment
- Building the continuous deployment process
- Automated Deployment Pipeline
- CI/CD Tool Selection

### Learning Objectives

1. The traditional delivery process
2. Drawbacks of the traditional delivery process
3. Introduction to Continuous Integration
4. Advantages of Continuous Integration
5. Continuous Delivery and Continuous Deployment
6. Continuous Delivery
7. Continuous Deployment
8. Advantages of Continuous Deployment
9. Pre-requisites to CI/CD
10. Introducing Tools for Continuous Delivery Process
11. Stages of a CI/CD pipeline
    - Source Stage
    - Build Stage
    - Test Stage
    - Deploy Stage
12. Implementation of CI/CD
13. CI/CD Tool Selection
    - Jenkins
    - TeamCity
    - Bamboo
    - Travis CI
    - Circle CI
14. Knowledge checks and quizzes


## Lesson 3: Getting Started With Jenkins

By the end of this lesson, you will be able to explain:

- Setting Up Git
- Connecting Git Repository
- Setting Up Jenkins
- Jenkins Installation and configuration
- Maven Set Up
- Adding Maven functionality
- Exploring Jenkins
- Building a Maven Project

### Learning Objectives

1. Preparing your environment
2. Configuring Version Control Tools
3. Installing and Setting Up Git
4. Configuring SSH Keys
5. Forking the Sample Repository
6. Assisted Practice/Demo: Working with Git
7. Introduction to Jenkins
8. Jenkins Configuration
9. Downloading and Installing Jenkins
10. Preparing a Build Server for Jenkins
11. Starting Up Jenkins
12. Assisted Practice/Demo: Setting Up Jenkins
13. Configuring the Dev Tools
14. Configuring Your Maven Setup
15. Configuring the JDK
16. Assisted Practice/Demo: Configuring Dev Tools
17. Understanding Jenkins Architecture
18. Plugins, Notifications, Backup, and Security
19. Pipelines
20. Introduction to BlueOcean
21. Assisted Practice/Demo: Exploring Jenkins and BlueOcean


## Lesson 4: Build Jobs and Configurations

By the end of this lesson, you will be able to explain:

- Jenkins Build Jobs
- Freestyle Build Jobs
- Creating a Freestyle Build
- Build Triggers
- Scheduled Build Jobs
- Polling the SCM
- Build Steps
- Jenkins Environment Variables
- Post-build Actions
- Building Other Projects
- Using Jenkins with Other Languages
- Gradle build
- Parameterized Build Jobs
- Parameterized Build Jobs
- Building from Tags
- Remote Triggering Parameterized Builds
- Enabling Security in Jenkins
- Enabling Security in Jenkins
- Build Pipelines and Promotions

### Learning Objectives

1. Creation of Jenkins build jobs
2. Types of Jenkins build jobs
3. Freestyle Build Jobs
   - General Configuration
   - Advanced Configurations
4. Configuring Source Code Management
   - Working with Subversion
   - Working with Git
   - Assisted Practice/Demo: Source Code Management
5. Build Triggers
   - Start a Build Job After Another
   - Scheduled Build Jobs
   - Assisted Practice/Demo: Build Triggers
6. Poll the SCM
7. Trigger Builds Remotely
   - Assisted Practice/Demo: Remote Triggering
8. Manual Build jobs
9. Build Steps
   - Maven Build Steps
   - Ant Build Steps
10. Using Jenkins Environment Variables in Your Builds
11. Post-build Actions
    - Reporting on Test Results
    - Archiving Build Results
    - Stable and Successful Builds
    - Notifications
    - Assisted Practice/Demo: Post-build Actions
12. Using Jenkins with Other Languages
    - Building Projects with Grails
    - Building Projects with Gradle
    - Assisted Practice/Demo: Building with Other Languages
13. Incremental Builds
14. Parameterized Build Jobs
    - Creating a Parameterized Build Job
    - Assisted Practice/Demo: Parameterized Build Jobs
15. Adapting Builds for Parameterized Build Scripts
16. Building from a Subversion Tag
17. Building from a Git Tag
    - Assisted Practice/Demo: Building from Tags
18. Starting a Parameterized Build Job Remotely
19. Parameterized Build Job History
20. Parameterized Triggers
    - Assisted Practice/Demo: Parameterized Triggers
21. Enabling Security in Jenkins
    - Different Levels of Authentication
    - Matrix-based Security
    - User Permissions
    - Role-based Security
    - Project-based Security
    - Assisted Practice/Demo: Enabling Security
22. Build Promotions
23. Build Pipelines


## Lesson 5: Configuring Build Pipelines

By the end of this lesson, you will be able to explain:

- Pipelines
- Pipeline Structure
- Defining a Pipeline
- Declarative Pipeline Syntax
- Scripted Pipeline Syntax
- Building a Pipeline
- Continuous Integration Pipeline
- Continuous Integration Pipelines
- Building Pipelines from Jenkinsfile
- Jenkinsfile
- Snippet Generator
- Snippet Generator
- Global Variable Reference
- Declarative Directive Generator
- Restarting a pipeline

### Learning Objectives

1. Pipelines
   - Why Pipeline?
   - Advantages of Pipeline
   - Pipeline Workflow
   - Pipeline Terminology
2. Defining a Pipeline
   - Benefits of Jenkinsfile
   - Scripted vs. Declarative Syntax
3. Declarative Pipeline Syntax
   - Pipeline Keywords
4. Scripted Pipeline Syntax
   - Assisted Practice/Demo: Scripted Pipeline Syntax
5. Building a Pipeline
   - Building Pipelines with Blue Ocean
   - Building Pipelines with the Classic UI
6. Commit Pipeline
   - Assisted Practice/Demo: Commit Pipeline
7. Jenkinsfile
   - Creating Jenkinsfile
   - Running Pipeline from Jenkinsfile
   - Build with Jenkinsfile
   - Test with Jenkinsfile
   - Deploy with Jenkinsfile
   - Assisted Practice/Demo: Jenkinsfile
8. Snippet Generator
   - Unassisted Practice/Demo: Snippet Generator
9. Global Variable Reference
10. Declarative Directive Generator
11. Restarting a pipeline
   - Unassisted Practice/Demo: Restarting a pipeline
12. Pipeline Development Tools


## Lesson 6: Automated Testing In Jenkins

By the end of this lesson, you will be able to explain:

- Jenkins as an Automation Testing tool
- CI with JUnit in Jenkins
- Code Coverage using JaCoCo
- Code Coverage using Clover
- Acceptance and Performance Tests in Jenkins
- Integrate JMeter with Jenkins

### Learning Objectives

1. Introduction
2. Automating Your Unit and Integration Tests
   - Configuring Test Reports in Jenkins
   - Displaying Test Results
   - Assisted Practice/Demo: Test Results
3. Ignoring Tests
4. Measuring Code Coverage with JaCoCo
   - Assisted Practice/Demo: JaCoCo
5. Measuring Code Coverage with Clover
   - Assisted Practice/Demo: Clover
6. Automated Acceptance Tests
7. Automated Performance Tests with JMeter
   - Assisted Practice/Demo: JMeter Integration


## Lesson 7: Code Quality Improvement using Jenkins

By the end of this lesson, you will be able to explain:

- Code Quality and Jenkins
- Internals of Jenkins Jobs
- FindBugs
- Code Complexity
- Reporting on Code Complexity
- Open Tasks
- SonarQube
- Integrate SonarQube with Jenkins

### Learning Objectives

1. Introduction
2. Code Quality in Your Build Process
   - Popular Java and Groovy Code Quality Analysis Tools
   - Checkstyle, PMD/CPD, FindBugs
3. Reporting on Code Quality Issues with the Violations Plugin
   - Working with Freestyle Build Jobs
   - Working with Maven Build Jobs
   - Using the Checkstyle, PMD, and FindBugs Reports
   - Assisted Practice/Demo: Code Quality Reports
4. Reporting on Code Complexity
   - Assisted Practice/Demo: Code Complexity Reports
5. Reporting on Open Tasks
6. Integrating with SonarQube
   - Assisted Practice/Demo: SonarQube Integration


## Lesson 8: Automated Deployment and Continuous Delivery

By the end of this lesson, you will be able to explain:

- Building the Continuous Delivery Process
- Implementing Automated and Continuous Deployment
- Deploying a Python application
- Tomcat and Jenkins
- PHP and Jenkins

### Learning Objectives

1. Introduction to Automated Deployment and Continuous Delivery
   - Continuous Delivery
   - Benefits of Continuous Delivery
2. Automated Deployment
   - Benefits of Automated Deployment
   - Automated Deployment Pipeline
   - Phases of Automated Deployment Pipeline
   - Tools Used
   - Automated Deployment System
3. Implementing Automated and Continuous Deployment
   - The Deployment Script
   - Database Updates
   - Smoke Test
4. Jenkins and Docker
5. AWS Pipeline
6. Deploying a Python application to an application server
   - Assisted Practice/Demo: Python Application Deployment
7. Tomcat and Jenkins
   - Assisted Practice/Demo: Deploying a Java Application with Tomcat and Jenkins
8. PHP and Jenkins
   - Assisted Practice/Demo: Deploying a PHP Application with Jenkins


## Lesson 9: Distributed System in Jenkins

By the end of this lesson, you will be able to explain:

- Distributed Architecture
- Create multiple slave nodes
- Deep Diving Jenkins Master/Slave Architecture
- Build job with a slave machine

### Learning Objectives

1. Introduction
   - The Jenkins Distributed Build Architecture
   - Master/Slave Strategies in Jenkins
2. Why Label Node?
   - Assisted Practice/Demo: Labeling Nodes
3. Creating Multiple Slave Nodes
   - The Master Starts the Slave Agent Using SSH
   - Starting the Slave Agent Manually Using Java Web Start
   - Associating a Build Job with a Slave or Group of Slaves
   - Assisted Practice/Demo: Setting Up and Managing Slave Nodes
4. Deep Diving Jenkins Master/Slave Architecture
   - Benefits and Use Cases for Distributed Builds
   - Managing and Monitoring Slave Nodes
5. Build Job with a Slave Machine
   - Configuring Build Jobs for Specific Slave Nodes or Labels
   - Assisted Practice/Demo: Running a Build Job on a Slave Machine


</details>


---------------------------------------------------------------------------------------------------------

## Optional : Scripted Pipeline VS Declarative Pipeline

<details>

| Feature                   | Scripted Pipeline                                            | Declarative Pipeline                                         |
|---------------------------|--------------------------------------------------------------|--------------------------------------------------------------|
| Syntax                    | Groovy-based DSL                                             | YAML-based DSL                                               |
| Structure                 | Procedural style, with stages defined as functions           | Declarative style, with stages defined as steps               |
| Stage definition          | Defined using `stage` step and block                         | Defined using `stages` section and `stage` steps             |
| Parallel stages           | Defined using `parallel` step and block                      | Defined using `parallel` directive                            |
| Agent definition          | Defined using `node` step and block                          | Defined using `agent` directive                               |
| Environment variables     | Defined using `env` map at the top of the script             | Defined using `environment` directive                         |
| Post-build actions        | Defined using `post` section                                 | Defined using `post` directive                                |
| Flow control              | Uses traditional `if-else` statements and loops              | Uses a declarative `when` directive for flow control          |
| Error handling            | Uses `try-catch-finally` statements for error handling        | Uses `catchError` and `error` directives for error handling   |
| Shared libraries support  | Supported                                                     | Supported                                                     |

</details>


# References: 
1. https://maven.apache.org/guides/getting-started/maven-in-five-minutes.html
2. https://maven.apache.org/download.cgi

# Disclaimer

Please note that the entire repository is owned and maintained by [Varun Kumar Manik](https://www.linkedin.com/in/vkmanik/). While every effort has been made to ensure the accuracy and reliability of the information and resources provided in this repository, Varun Kumar Manik takes full responsibility for any errors or inaccuracies that may be present.

Simplilearn is not responsible for the content or materials provided in this repository and disclaims all liability for any issues, misunderstandings, or claims that may arise from the use of the information or materials provided. By using this repository, you acknowledge that Varun Kumar Manik is solely accountable for its content, and you agree to hold Simplilearn harmless from any claims or liabilities that may arise as a result of your use or reliance on the information provided herein.

It is important to understand that this repository contains educational materials for a training course, and users are expected to apply their own judgment and discretion when utilizing the provided resources. Neither Varun Kumar Manik nor Simplilearn can guarantee specific results or outcomes from following the materials in this repository.


## Connect & Follow
