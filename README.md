Watch the demo at https://youtu.be/GIM5irN4Ix0

# Getting Started

Clone the project:

    git clone https://github.com/dgonzo27/react-docker-gcp.git
    
Navigate into the directory:

    cd react-docker-gcp
    
Install node modules:

    npm install
    
Run the app locally:

    npm start
    
Build the docker image:

    docker build -t react-docker-gcp:latest .
    
Run the docker image:

    docker run -p 8080:443 react-docker-gcp:latest
    
Navigate to the url in your browser:

    http://localhost:8080
