# cf-airflow
A rudimentary example for running Apache Airflow on Cloud Foundry.  
(Replace all occurrences of IMAGE_NAME[:TAG] with an image name that you want to use)

### Build the image and push to a registry. 
Clone the repo or download the code.  

docker build -t IMAGE_NAME[:TAG] .  
docker push IMAGE_NAME[:TAG]

### Push the app to Cloud Foundry
cf push -f manifest.yml

