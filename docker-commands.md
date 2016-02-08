#Link per installazione
https://docs.docker.com/engine/installation/linux/centos/#prerequisites:edbc1ead8377994ecc0cbf4889b1c013 : istruzioni per installare docker.

* Comandi:
	* docker run hello-world: testiamo la installazione di docker qui sulla CentOS 7 64bit
	* docker pull ubuntu:14.04
	* docker run ubuntu:14.04 : creazione della immagine.
	* creare il Dockerfile in una directory e lanciare: docker build test. nel docker file si fa riferimento alla ubuntu image creata prima. 
	* docker run -i -d (numero della immagine)
	* docker ps : verifica il container che sta girando con la immagine precedentemente creata
