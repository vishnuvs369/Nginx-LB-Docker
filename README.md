# This is the docker files for running nginx containers as Loadbalancer

Directory Structure:

Your directory structure should look like this:
Copy code
.
├── Dockerfile.nginx1
├── Dockerfile.nginx2
├── loadbalancer.conf
├── nginx1_content
│   └── index.html
├── nginx2_content
│   └── index.html
└── docker-compose.yml


Build and Run:
In your project directory, run the following command to build and start the containers:
docker-compose up --build

