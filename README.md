# How to run
Make the web archive and save it to temp.war
```
jar -cvf temp.war src/main/webapp/*
```
Make sure you have docker installed
```
docker build -t temp .
docker run --rm -dp 8080:8080 temp
```
Now open this in your browser

http://localhost:8080/temp/src/main/webapp/index.jsp
