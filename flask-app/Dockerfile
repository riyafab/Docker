#getting Base image
FROM python:3.9

#WOrking directory where all the code will be kept
WORKDIR app/

#Copy the app to the directory of the container
COPY app.py .

#Insatll reqired libaries
RUN pip install flask

#Run pyhton  compiled code
CMD ["python","app.py"]
