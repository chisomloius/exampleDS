# the container you want to start up
FROM python:3.9.1

# this dependencies you want to install  into the container
# you can install more than one dependencies
RUN pip install pandas

# working directory of the image
WORKDIR /app

# this will copy the source file to destination file
COPY pipeline.py pipeline.py

# this substitutes the bash paramter when using command - Docker run -it (container nam) 'bash'
# configures the container to run as an executable
ENTRYPOINT [ "python", "pipeline.py" ]

## ORIGINAL FILE
FROM pyth
