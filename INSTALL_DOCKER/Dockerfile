FROM windev/webdev-base:US240063m

COPY Darlene Project.ZIP ${WEBDEVConfiguration}comptes/ftp_webdev/

RUN set -ex \
	&& cd ${WEBDEVBinaries} \
	&& ${WEBDEVBinaries}WDInstalle /DOCKER/INSTALLEGO/Darlene Project

# Création de la persistance
VOLUME ${WEBDEVConfiguration}comptes/Donnees/Darlene Project/