![Starbucks Clone Deployment](https://github.com/user-attachments/assets/6b654f47-9537-4b88-9584-41c760fc49ac)
## Jenkins Pipeline Code Configuration
This screenshot highlights the Jenkins Pipeline interface, showing the structured pipeline code in the [Jenkinsfile](JenkinsFile). The stages visible include:
- **SonarQube Analysis:** Code quality scan stage configured for static analysis.
- **OWASP FS Scan:** Integration of OWASP Dependency Check for checking vulnerabilities in third-party libraries.
- **Trivy Scan:** Docker image scanning for vulnerabilities.
- **Docker Build and Deployment:** Stages showing Docker image build and its deployment process.
![Jenkins Pipeline Code Configuration](https://github.com/user-attachments/assets/0cd8dffe-0238-49c6-8b5b-97b3a3dd33ad)

---
## SonarQube Analysis Results
This screenshot captures the SonarQube dashboard showing results of the analysis performed on your code. The key details visible include:
- **Code Quality Metrics:** Overview of code coverage, bugs, and code smells.
- **Vulnerabilities:** Highlighting any security vulnerabilities found during analysis.
- **Overall Health:** Quality gate status (whether the code meets defined standards) and recommendations for improvement.

![SonarQube Analysis Results](https://github.com/user-attachments/assets/65f6d35d-3822-4383-9d38-5a42a98ab5b6)

---
## Docker Image Pushed to Docker Hub
- This screenshot shows the output of the successful `docker push` command, either from Jenkins or the CLI. It displays the Docker image being pushed to Docker Hub, along with version tags and image layers uploaded. In addition, the Docker Hub interface confirms the presence of the pushed image under the specified repository.
![Docker Image Pushed to Docker Hub](https://github.com/user-attachments/assets/750f2007-c3fb-42d2-8808-a8424a1930f7)
---
## Website Deployment Output
This screenshot captures the running application after deployment, showing the website's frontend in a web browser. The URL or local port where the application is running is displayed, confirming that the deployment was successful and the website is accessible. The output reflects the final, user-facing result of your entire CI/CD pipeline.

![Website Deployment Output](https://github.com/user-attachments/assets/fe7a8146-da2f-40d1-9430-ef7b577eb385)

