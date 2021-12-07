# operations-task



### Get the clone from the repository using below command
  ```
  git clone https://github.com/sanjeewanie/operations-task.git
  ```
  
Make sure your developemnt envirentment have below aplications up and running.
  * Docker
  * Git
  
if you wish to change postgress mysql user credential you want to change the credentials in   Docker file and the config.py under "rates" folder.
#### You should navigate to operations-task path before build the Docker container.

### Build the Docker image and make application up

Run the Docker image to make application server up with Gunicorn master node and we can access the application  running on http://localhost:3000 
 ```
 docker-compose up --build
 ```
 
 
 ### You can test the application envirenment is up and runnnig using below command   
 curl "http://localhost:3000"
 


