# FROM indicates base image to use.  This indicates version of python to use
FROM python:3
# ADD includes the python script/executable
ADD simple.py /
# Uncomment RUN cmd below in order to include pystrich library if needed
## RUN pip install pystrich
# This runs the python script
CMD [ "python", "./simple.py" ]