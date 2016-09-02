# Experimenting with Apache Spark 2.0

## Goals
I am most interested in in the new pipelines for MLLib and the SQL interface.

There are a few notebooks with my worked examples of querying data loaded from a CSV file using the dataframe-API. I also train a few models using the pipeline framework. It's pretty slick.

## Set up

You can run the code in a docker image I got from [here](https://hub.docker.com/r/ezamir/jupyter-spark-2.0/). I volumed in the contents of the work folder to the /home/jovyan directory. that allows your notebooks and data. You can use the command:
> docker run ezamir/jupyter-spark-2.0 -p 8888:8888 -v <host/path/on/your/machine>:/home/jovyan/work
