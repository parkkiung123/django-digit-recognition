# django-digit-recognition
code is in docker image
docker image is built with windows

docker pull parkkiung123/django-webcam<br>
docker run -p 8000:8000 -p 9000:9000 -it parkkiung123/django-webcam python3 /root/django-webcam/djangodigit/run.py

use server_rootCA.pem file for https, set the pem file to the browser ssl setting 

## reference
https://cmusatyalab.github.io/openface/
