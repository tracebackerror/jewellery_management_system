# Jewellery Manaagement System on Docker Container

## How to Run
**0. Build From Source(Optional)
<br>
`docker buildx build --no-cache -t tracebackerror/jewellery_management_system .`

**1. Pull the Docker Image from Cloud**
<br>
`docker pull tracebackerror/jewellery_management_system:latest`


**2. Run the Container**
<br>
`docker run -d -p 8000:8000 tracebackerror/jewellery_management_system`