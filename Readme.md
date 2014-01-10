Rabbit MQ application sample.
===================================

How install and build rabbit mq server from source code:
----------------------------------------------------------

	sudo apt-get install mercurial

	hg clone http://hg.rabbitmq.com/rabbitmq-codegen
	hg clone http://hg.rabbitmq.com/rabbitmq-server

	sudo apt-get install libxml2-dev libxslt-dev
	sudo apt-get install xsltproc

	cd rabbitmq-server
	make

Start from console:
	make run

Start from script:

	cd scripts 
	sudo ./rabbitmq-server

Check status:
	sudo ./rabbitmqctl status