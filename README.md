# redis
redis

### redis ###
##### 安装 #####
###Installation Download, extract and compile Redis with: ###
    $ wget http://download.redis.io/releases/redis-3.2.1.tar.gz 
    $ tar xzf redis-3.2.1.tar.gz 
    $ cd redis-3.2.1 
    $ make 
###The binaries that are now compiled are available in the src directory. Run Redis with:### 
$ src/redis-server 
###You can interact with Redis using the built-in client:### 
    $ src/redis-cli 
    redis> set foo bar OK 
    redis> get foo "bar"
