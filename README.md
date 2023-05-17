# digitalocean-fastapi-template
## Clone the repo 
git clone https://github.com/PixelPunk2077/digitalocean-fastapi-template.git
## Build Docker Image
Build docker image 
## Testing 
docker run -dp 8080:8080 fastapi_app:latest
## Push Docker Image to Docker Hub
docker login 
###tag the image with a path in your Container Registry
docker tag image_name:image_version registry-name/image_name:image_version
### docker push command
docker push image_name

