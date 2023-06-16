#FROM its about the image that you will utilize
FROM python:3.9
#RUN is some command 
RUN pip install pandas

#Directory to files
WORKDIR /app

#Copy depedences from mycomputer to the image
COPY pipeline.py pipeline.py

#ENTRYPOINT is the command after the image is executed
ENTRYPOINT [ "python","pipeline.py" ]
#To build a dockerfile you need to run docker build -t test:pandas .