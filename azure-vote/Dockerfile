# Pull the base image
FROM tiangolo/uwsgi-nginx-flask:python3.8

# Copy the content of the current directory to the /app of the container
ADD . /app

# Install depndencies 
RUN pip install --requirement /app/requirements.txt
