#imagem inicial
FROM ubuntu:12.04

#mantedor
MAINTAINER Pedro Lazari

#instalar os apps
RUN apt-get update && \
	apt-get install -y apache2 && \
	echo "pedro lazari esta fazendo acontecer"

# Ports exposes
EXPOSE 80

#After execution
CMD /etc/init.d/apache2 start
#CMD ["/usr/sbin/apache2ctl", "-D FOREGROUND"]
