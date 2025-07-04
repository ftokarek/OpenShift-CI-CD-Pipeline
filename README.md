# CI/CD Tools and Practices – Final Project

This repository contains the implementation of the final project for the **Continuous Integration and Continuous Delivery (CI/CD)** course on Coursera, developed in the IBM Skills Network Labs environment as a part of the IBM DevOps and Software Engineering certificate.

The goal of this project is to design and execute a complete **Continuous Integration and Continuous Delivery (CI/CD)** pipeline using modern DevOps tools including **GitHub Actions**, **Tekton** and **OpenShift**.

## ✅ Key Features

- CI pipeline in **GitHub Actions** for:
  - Code linting
  - Unit testing

- CD pipeline with **Tekton on OpenShift** for:
  - Linting and testing using Tekton Tasks
  - Building container images
  - Deploying to the OpenShift cluster

- Automated end-to-end delivery of code changes using cloud-native tools.

## 🛠️ Setup

After launching the lab environment, install the required dependencies by running:

```bash
bash bin/setup.sh
```

Then you must exit the shell and start a new one for the Python virtual environment to be activated.

```bash
exit
```

## License

Licensed under the Apache License. See [LICENSE](/LICENSE)

## 👤 Author

This project was initially created by **Skills Network** as part of the IBM Coursera course.  
It was further extended and customized by **Franciszek Tokarek** for the final capstone implementation.

## <h3 align="center"> © IBM Corporation 2023. All rights reserved. <h3/>
