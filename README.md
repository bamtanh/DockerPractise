#docker Practice
### Installation
<pre>
cd /home
git clone https://github.com/bamtanh/DockerPractise
cd DockerPractise
</pre>

### Run
<pre>
# Login For public Docker Repository
docker login
docker pull bamtanh/docker-practise
docker run -p 9876:80 -v /home/ubuntu/DockerPractise/Project:/var/www/html bamtanh/docker-practise
</pre>
