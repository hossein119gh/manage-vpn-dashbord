**Project Documentation: Setting up and Using Docker Image for ASP.NET Core Project with SQLite Database**

This document provides step-by-step instructions for setting up and using a Docker image for an ASP.NET Core project with a SQLite database.

### Step 1: Pull Docker Image
1. Open your terminal or command prompt.
2. Use the following command to pull the Docker image from Docker Hub:
    ```
    docker pull hossein119gh/manage-vpn-dashbord:latest
    ```

### Step 2: Run Docker Container
1. After pulling the Docker image, run a container based on this image.
2. Use the following command to run the container:
    ```
    docker run -d -p 8090:8080 --name mvd-container hossein119gh/manage-vpn-dashbord:latest
    ```
    - This command runs the container in detached mode (`-d`), maps port 8090 of the host to port 8080 of the container (`-p 8090:8080`), and names the container `mvd-container`.

### Step 3: Access Website
1. Open a web browser.
2. Enter the IP address of your server followed by port 8090 (e.g., `ipserver:8090`) in the address bar.
3. Press Enter to navigate to the website.
4. for example : http://5.75.198.59:8090/

### Additional Notes:
- Ensure that Docker is installed on your system before following these steps.
- Replace `ipserver` with the actual IP address of your server where the Docker container is running.
- Make sure that port 8090 is not blocked by any firewall settings.
- For troubleshooting or further assistance, refer to the Docker documentation or seek help from the project's support channels.

By following these steps, you should be able to set up and use the Docker image for your ASP.NET Core project with SQLite database successfully.
