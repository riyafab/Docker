#Getting Base image
FROM openjdk:11

#Working directory where all code will be kept
WORKDIR app/

#Copy the app to the current working directory
COPY Hello.java .

#Complie the code
RUN javac Hello.java 

#run java compliled code
CMD ["java","Hello"]
