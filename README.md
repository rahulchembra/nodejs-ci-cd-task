This is a simple Node.js application integrated with a full CI/CD pipeline using Docker and GitHub Actions. 
The project includes a `Dockerfile` to containerize the app and a GitHub Actions workflow file located at `.github/workflows/main.yml`. 
The CI/CD pipeline is triggered on every push to the `main` branch. 
It installs dependencies, runs tests, builds a Docker image, logs in to DockerHub using GitHub secrets (`DOCKER_USERNAME` and `DOCKER_PASSWORD`), 
and automatically pushes the image to DockerHub at `rahulchembra/nodejs-demo-app`. 
You can run the app locally using `npm install` and `node index.js`, or run it in Docker using `docker build` and `docker run`.
