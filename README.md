# docker-python-helloworld
Dockerise Python Code

```
git clone https://github.com/mohodk92/docker-python-helloworld.git
cd docker-python-helloworld
```
```
sudo yum install python -y
python --version
sudo yum install tree -y
tree --version
sudo systemctl status docker
sudo mkdir project
cd project
pwd
tree
sudo touch helloworld.py
sudo touch dockerfile
tree
sudo nano helloworld.py 
cat helloworld.py 
python --version
sudo docker login
sudo nano dockerfile 
cat dockerfile 
cat helloworld.py 
python3 helloworld.py 
sudo docker build -t mohodk92/pythonhelloworld .
sudo docker images
sudo docker run mohodk92/pythonhelloworld
sudo docker container ls
sudo docker ps -a
sudo docker push mohodk92/pythonhelloworld
sudo docker pull mohodk92/pythonhelloworld
sudo docker run mohodk92/pythonhelloworld
```
