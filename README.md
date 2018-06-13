# Testing pyspark on Mac OSX  
## Installation guide:  
- install anaconda  
- install Java 1.8 development toolkit (I had issues with Java 10 on my Mac)  
- put anaconda, spark, and java 1.8 into your environment (.bashrc):
```
export PATH=/anaconda3/bin/:$PATH  
export SPARK_HOME=/Users/flender/projects/spark-2.3.1-bin-hadoop2.7/  
export PATH=$SPARK_HOME/bin:$PATH  
export JAVA_HOME=/Library/Java/JavaVirtualMachines/jdk1.8.0_171.jdk/Contents/Home/  
```
- for running the pyspark REPL, simply type pyspark  
- for running a notebook, first source env.sh. Then type pyspark.  