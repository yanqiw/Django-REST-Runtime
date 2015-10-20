# Django-REST-Runtime
This repo is used to build Django REST Runtime for development

#Usage
##Build image on your machine
```bash
git clone git@github.com:yanqiw/Django-REST-Runtime.git
cd Django-REST-Runtime
docker build -t django-rest-runtime .
```
## Run the container
```bash
cd /to/you/code
docker run --name project-runtime -p 8000:8000 -v "$PWD":/code -d django-rest-runtime
```
