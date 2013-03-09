arquitectura-java-solida
========================

Desarrollando Arquitectura Java Sólida

Capitulo 1. HTML

Capitulo 2. Java Server Pages

	Tarea 1. Creación de una tabla de libros

		> mysql -u root -p
		Password:
		mysql > CREATE DATABASE arquitecturajava;
		mysql > USE arquitecturajava;
		mysql > CREATE TABLE Libros (isbn VARCHA(10) PRIMARY KEY, Titulo VARCHAR(30), Categoria VARCHAR(30));
		mysql > CREATE USER 'birlibirloque'@'localhost' IDENTIFIED BY 'birlibirloque1';
		mysql > GRANT ALL ON arquitecturajava.* TO 'birlibirloque'@'localhost';

