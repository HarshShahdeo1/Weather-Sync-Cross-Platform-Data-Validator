# Weather-Sync-Cross-Platform-Data-Validator
Weather-Sync is a unified test automation ecosystem designed to validate data consistency across Web, Mobile, and API layers. The project ensures weather data from a REST API matches the front-end UI on Web and Mobile interfaces, fulfilling the requirements of the CSV301: Test Automation course
1. Introduction
Weather-Sync is a unified test automation ecosystem designed to validate data consistency across Web, Mobile, and API layers. Developed as part of the CSV301: Test Automation course, this project demonstrates the integration of test automation into DevOps and CI/CD pipelines. It moves beyond local execution by utilizing cloud-based services like AWS and Azure for a scalable and efficient testing infrastructure
2. Problem Statement
In modern cloud-based applications, ensuring data parity between backend services and frontend interfaces is complex. Manual verification is insufficient for handling:
Mobile-Specific Challenges: Managing device orientations, permissions, and network connectivity.
Scalability: The need for cost-effective and accessible testing resources that go beyond local machine capabilities.
Continuous Delivery: The difficulty of maintaining test scripts and monitoring results proactively within a fast-paced DevOps environment.
3. Objectives
The project aims to achieve the following Course Outcomes (COs):
Unified Framework: Demonstrate automation tools for web, mobile, and API testing within a single suite.
Mobile Mastery: Determine appropriate automation for mobile applications using Appium with mobile drivers.
DevOps Integration: Integrate automated testing into CI/CD pipelines for continuous delivery.
Cloud Infrastructure: Leverage AWS and Azure services for scalable test execution and resource provisioning.
Strategic Testing: Devise and implement effective test automation strategies for cloud-based applications.
4. Methodology
The project implements a multi-phase testing strategy:
API Testing (Unit IV): Initial functional testing and request design using Postman, followed by automated validation of responses and errors using Rest Assured.
Web Application Testing (Unit II): Using Selenium WebDriver to locate and interact with web elements, handle assertions, and generate comprehensive reports.
Mobile Application Testing (Unit III): Testing native and mobile web apps with Appium, specifically addressing challenges like screen orientation and app launches.
Cloud Integration (Unit V): Establishing cloud-based environments on AWS and Azure to facilitate remote test execution.
CI/CD Execution (Unit VI): Setting up pipelines with Jenkins to prioritize test cases and optimize execution.
5. Tools and Software
This project utilizes Selenium , Appium , Postman , Rest Assured , AWS , Azure , and Jenkins.
