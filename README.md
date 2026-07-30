1. Create a new directory for the project 
```bash
mkdir hello-docker
```
2. Move the Dockerfile to the directory
 ```bash
mv Dockerfile hello-docker/
```
3. Enter the directory
```bash
cd hello-docker/
```
4. Build the image
```bash
sudo docker build -t hello-captain .
```
# -t (tag) gives the image a name 
5. Run the container
```bash
sudo docker run hello-captain
```bash
   
