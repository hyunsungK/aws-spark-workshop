# EMR Workshop

 
 ## Getting Started

 - Enabling pipenv
 ```
 PIPENV_VENV_IN_PROJECT=true pipenv install --three
 ```

- Installing Pyspark
```
pipenv install pyspark
```

- Running a program
```
python spark-etl.py ./dataset/input ./dataset/output/spark 
```

- Submit 
```
spark-submit spark-etl.py ./dataset/input/ ./dataset/output/spark
```

## Pre-requsitive

- Java Runtime
```
brew install homebrew/cask-versions/adoptopenjdk8
```

- Installing Scala
```
brew install scala
``` 

- Installing Spark
```
brew install apache-spark
```
