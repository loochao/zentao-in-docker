# zentao-in-docker
Using docker-compose to deploy zentao in docker . 

## how to use

* update your /etc/hosts, add content below :

		127.0.0.1 testc.com

* run ``` docker-compose up -d ```

	the php will auto install pdo_mysql and mysqli by himself. 

* when install zentao , plz pay attention that mysql's address should be 'mysql':

	![1.jpg](https://github.com/liumapp/zentao-in-docker/blob/master/pic/1.jpg)

