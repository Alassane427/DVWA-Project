# Module 6 – Setup Log  
**Name:** Alassane Camara  
**Course:** CSN190  
**Assignment:** 6.2 – Setup and Deploy First Project  

---

## 🧩 Project Information
- **Project Cloned:** [Damn Vulnerable Web Application (DVWA)](https://github.com/digininja/DVWA)  
- **Purpose:** DVWA is a PHP/MySQL web application designed to help cybersecurity students practice finding and fixing common web vulnerabilities in a safe, controlled environment.

---

## ⚙️ Steps Followed

### Step 1 – Install Visual Studio Code
- Downloaded and installed **VS Code** from [code.visualstudio.com](https://code.visualstudio.com/).  
- Launched VS Code to confirm the installation worked.

### Step 2 – Create Project Folder
- Created a folder on the desktop named **CSN190** to store all class projects.

### Step 3 – Install Docker Desktop
- Installed **Docker Desktop for Windows**, which provides Docker Engine and Docker Compose.  
- Verified Docker was running (green whale icon visible in the system tray).

### Step 4 – Clone the DVWA Repository
- Clone repository inside VS code and save it to created folder

### Step 5 – Deploy and Verify Deployment
- run "docker compose up" in VS terminal in dvwa folder
- Opened a web browser and visited http://localhost:4280.
- Confirmed that the DVWA login page appeared, showing that the project was running successfully.

| Problem                                   | Cause                                     | Solution                                         |
| ----------------------------------------- | ----------------------------------------- | ------------------------------------------------ |
| DVWA site didn’t load at first            | Database container was still initializing | Waited 20–30 seconds, then refreshed the browser |
| Unsure if containers were active          | Needed to verify container logs           | Checked logs in Docker Desktop and terminal      |
| Confused about Docker Desktop requirement | VS Code alone can’t run Docker commands   | Installed Docker Desktop to enable Docker Engine |


# VS Code open with CSN190 folder
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/8c0c57d1-77ff-4e06-bc32-e4e78bd97411" />

# Docker Desktop running
<img width="1593" height="907" alt="image" src="https://github.com/user-attachments/assets/c2f3f572-b87d-4b12-bba6-39f4f4994ebf" />

# Terminal output from docker compose up
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/7550c14f-bed5-4482-99b6-d2a0283a2807" />

# Containers running successfully
<img width="1593" height="907" alt="image" src="https://github.com/user-attachments/assets/20911b57-d8ca-4166-a5e6-e944ae36cfef" />

# DVWA login page at http://localhost:4280
<img width="960" height="1020" alt="image" src="https://github.com/user-attachments/assets/9dc78c79-0a1c-4e2a-9b6a-65513faf469c" />

### Summary 
- Successfully cloned and deployed the Damn Vulnerable Web Application (DVWA) locally using Docker Compose inside Visual Studio Code.
This process demonstrated how to run a real-world cybersecurity lab environment using containerization tools.
Gained experience managing containers, troubleshooting deployment issues, and verifying a working local web application setup.
