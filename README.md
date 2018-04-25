# spark
export SPARK_HOME=/usr/local/spark
export PYTHONPATH=$SPARK_HOME/python:$SPARK_HOME/python/lib/py4j-0.10.6-src.zip:$PYTHONPATH
export PATH=$HADOOP_HOME/bin:$SPARK_HOME/bin:$PATH
export LD_LIBRARY_PATH=$LD_LIBRARY_PATH:/usr/local/hadoop/lib/native${LD_LIBRARY_PATH:+:${LD_LIBRARY_PATH}}

export PYSPARK_DRIVER_PYTHON="jupyter"
export PYSPARK_DRIVER_PYTHON_OPTS="notebook"
export PYSPARK_PYTHON=python3

export HIVE_HOME=/usr/local/hive
export PATH=$PATH:$HIVE_HOME/bin
