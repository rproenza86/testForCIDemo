# Test app for bTreePress course on Continous Integration with Docker
This is a quick  node.js appfor the purposes of demonstrating a basic CI/CD workflow with Docker Hub for How To Use Docker With Continous Integration To Build A DevOps Automated Workflow .
This Project Is Included In the Exercise Files  
and @  
**GitHub:**   
https://github.com/bTreePress/Docker-With-Continous-Integration

## Instructions  

download or pull to your local computer
https://github.com/bTreePress/Docker-With-Continous-Integration.git

In the root of the project folder run 
```javascript
npm install
```
To Start the site run 
```
node . 
```
To View The Site go to:  
**http://localhost:8080**

Note for the final Chapter I make a chnage to the home.hbs view to show the code going through the entire process. I put that code in a seperate file called home-cat.hbs.


## Steps in the automatization process:

1. NodeJs app with its unit test and stored in Github or Bitbucket 
2. CircleCI account bind with the version control repository
3. CircleCI app configuration
4. DockerHub or any other container repository account
5. DockerHub automated build configuration link with github 
6. DockerHub automated TRIGGER build configuration for the automated build configuration
7. CircleCI Environment Variables config for the Docker TRIGGER url
