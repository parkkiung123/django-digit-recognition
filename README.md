# django-digit-recognition
code is in docker image<br>
docker image is built with windows

docker pull parkkiung123/django-webcam<br>
1. django-webcam 7-segment digit recognition<br>
docker run -p 8000:8000 -p 9000:9000 -it parkkiung123/django-webcam python3 /root/djangodigit/run.py<br>
2. django-webcam face recognition<br>
docker run -p 8000:8000 -p 9000:9000 -it parkkiung123/django-webcam python3 /root/djangodigit/run.py<br>

connect to http://localhost:8000

## reference
https://cmusatyalab.github.io/openface/
