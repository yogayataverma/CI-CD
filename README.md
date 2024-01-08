# Jenkins Hello World Java Project

## To Run the Project:

1. **Clone the Repository:**
   - Clone this repository to your local machine.
  
2. **Download and Configure Jenkins:**
   - Download Jenkins from [here](https://www.jenkins.io/download/).
   - Follow the installation instructions for your operating system.
   - Set up Jenkins according to your requirements and configure it.

3. **Create a Jenkins Job:**
   - Open Jenkins in your web browser.
   - Create a new Jenkins job:
     - Choose "New Item" from the Jenkins dashboard.
     - Enter a job name and select "Freestyle project" or the appropriate project type.
     - Configure the job as needed, including linking the repository.

4. **Configure Build Steps:**
   - In the Jenkins job configuration, add build steps:
     - Choose "Execute shell" or "Execute Windows batch command" based on your operating system.
     - Use the following script to run the Java files:
       ```bash
       #!/bin/bash
       
       # Clone the repository
       git clone https://github.com/your-username/your-repo.git
       
       # Navigate to the project directory
       cd your-repo
       
       # Compile and run the Java files
       javac HelloWorld1.java
       java HelloWorld1
       
       javac HelloWorld2.java
       java HelloWorld2
       
       javac HelloWorld3.java
       java HelloWorld3
       
       javac HelloWorld4.java
       java HelloWorld4
       ```

5. **Save and Build:**
   - Save the Jenkins job configuration.
   - Run the Jenkins job.

6. **View Console Output:**
   - Check the console output of the Jenkins job for the execution details.

Congratulations! You have successfully configured Jenkins to clone the repository and run the Hello World Java files using the provided script. Adjust the script and job configuration based on your project's specifics.

Happy coding! 🚀
