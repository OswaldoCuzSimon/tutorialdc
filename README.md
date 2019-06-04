~~~
wget https://raw.githubusercontent.com/h2oai/h2o-3/master/Dockerfile
docker build -t "h2o.ai:v5" .
docker run -ti -p 54321:54321 h2o.ai:v5 /bin/bash
~~~

~~~
cd /opt && java -Xmx1g -jar h2o.jar
~~~
