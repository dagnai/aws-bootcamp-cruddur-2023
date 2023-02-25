FROM python:3.10-slim-buster

# Inside Container
# make a new folder inside container
WORKDIR /backend-flask

# Outside Container -> Inside Container
# this contains libraries that we want to install to run the app
COPY requirements.txt requirements.txt
# Inside Container
# Install python library used for the app
RUN pip3 install -r requirements.txt
# Outside Container -> Inside Container
# period ( . ) means everything in the current directory
# first . represents everything in /back-end flask (outside container)
# second . represents /back-end flask (inside container)
#aka. copy from one dir of outside container to another dir inside container
COPY . .

# Set Environment Variables (env vars)
#inside container and will remain set when the container is running!
ENV FLASK_ENV=development

EXPOSE ${PORT}

# CMD standa for command
# python3 -m flask run --host=0.0.0.0 --port=4567
CMD [ "python3", "-m" , "flask", "run", "--host=0.0.0.0", "--port=4567"]