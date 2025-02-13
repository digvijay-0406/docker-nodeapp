**Project Title:** Automated Deployment of Node.js Application with Jenkins & Docker

**Project Overview:**\
This project focuses on automating the deployment of a Node.js application using Jenkins and Docker. The objective is to streamline the development-to-deployment workflow by integrating containerization and continuous deployment strategies.

**Technologies Used:**

- **Jenkins** (for CI/CD automation)
- **Docker** (for containerization)
- **Node.js** (application runtime)
- **Shell Scripting** (for automation)

**Project Workflow:**

1. **Build Job:**

   - Pulls the latest source code from the repository.
   - Builds a Docker image from a **Dockerfile**.
   - Tags the image and optionally pushes it to a **Docker registry**.

2. **Test Job:**

   - Pulls the pre-built image (if stored in a registry) or uses the locally available image.
   - Runs a container using the image to validate application functionality.
   - Checks whether the container remains up for a certain time to ensure stability.

3. **Deployment Process:**

   - Ensures the container runs smoothly in a live environment.
   - Implements automatic updates via Jenkins, triggering deployments upon code changes.

**Key Achievements:**

- Successfully **containerized** a Node.js application.
- Automated the **build and test pipeline** using Jenkins.
- Implemented **continuous deployment** with seamless application updates.
- Used **Jenkins plugins** such as **Docker Pipeline** and **SSH Server** for efficient execution.
- Ensured application reliability by using **automated container management**.
- Verified **container stability** by checking its uptime during testing.

This project demonstrates expertise in **DevOps practices, containerization, and CI/CD automation**, providing a scalable and efficient deployment solution.

