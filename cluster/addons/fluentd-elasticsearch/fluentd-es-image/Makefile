.PHONY:	build push

TAG = 1.2

build:	
	sudo docker build -t kubernetes/fluentd-elasticsearch:$(TAG) .

push:	
	sudo docker push kubernetes/fluentd-elasticsearch:$(TAG)
