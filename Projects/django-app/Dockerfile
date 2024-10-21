#BASE IMAGE
FROM python:3.7

#WORKING DIRECTORY
WORKDIR /app

#CODE
COPY . .

#INSTALL LIBRARIES
RUN pip install -r  Requirements.txt

#MIGRATIONS
RUN python cool_counters/manage.py migrate

#RUN
CMD ["python","cool_counters/manage.py","runserver","0.0.0.0:8000"]






