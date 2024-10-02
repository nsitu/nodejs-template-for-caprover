# NodeJS Template for CapRover
This template can be used as a base for a new repository that will deploy itself to CapRover on every push. It assumes the use of NodeJS. GitHub Actions makes a tarball from the files and sends them to CapRover for building and Deploying. The build process happens according to the configuration in `Dockerfile`

# Usage
To use this template:
- In Caprover create a new APP, and record its name, e.g.  "my-app"
- Also in CapRover, create a secret TOKEN for the app (in the Deployment Tab)
- Make Note of the SERVER domain of your caprover (e.g. https://captain.mydomain.com )
- In GitHub Make a new repository from this template
- Once created, go to the repo settings and add APP, TOKEN, and SERVER as secrets.
- Push an update and the app should deploy build and deploy automatically
  
