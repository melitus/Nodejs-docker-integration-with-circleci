# Nodejs-docker-integration-with-circleci
Node.js web app with docker tracked on GitHub, configured on CircleCI 
A small node.js web app (and small test) will be uploaded and tracked on GitHub. GitHub will be configured to inform the CircleCI platform whenever code updates are committed and pushed. CircleCI will perform test builds. Upon successful test builds, CircleCI will inform Docker Hub, which in turn will trigger a new Automated Build and inform the Tutum container platform. Tutum will then pull the new Docker image and deploy it as a container on the Amazon Web Service platform
