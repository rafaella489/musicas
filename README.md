# musicas

CREATE DATABASE Musicas;

USE MUsicas;

CREATE TABLE favorita (
  ID int,
  nome varchar(255),
  artista varchar(255),
  idioma varchar (255),
  duracaomin int
  );

INSERT INTO `favorita`(`ID`, `nome`, `artista`,`idioma`, `duracaomin`)
VALUES
(1,'Fernando de Noronha','Mc IG','Portugues','8'),
(2,'StarBoy','The Weeknd','Inglês','3'),
(3,'Save your Tears','The Weeknd e Ariana Grande','Inglês','3'),
(4,'What do You Mean ','Justin Bieber','Inglês','3'),
(5,'3 dias virados','Mc IG','Portugues','3'),
(6,'Rather Be','Clean Bandit','Inglês','3'),
(7,'Im the One','DJ Khaled','Inglês','4'),
(8,'Anos de Luz','Matue','Portugues','4'),
(9,'Kenny G','Matue','Portugues','3'),
(10,'Rodeo Remix','Lah Pat','Inglês','4'),
(11,'Or Nah','The Weeknd','Inglês','4'),
(12,'Out West','Travis Scott','Inglês','2'),
(13,'Perdoa Por Tudo Vida','Veigh','Portugues','2'),
(14,'Promiscuous','Nelly Furtado','Inglês','4'),
(15,'Eu sou 157','Racionais','Portugues','8'),
(16,'GoodNight Menina 3','Mc IG','Portugues','3'),
(17,'É isso BB, ta certa','Mc IG','Portugues','4'),
(18,'Heartless','Kenye West','Inglês','3'),
(19,'Maria','Justin Bieber','Inglês','4'),
(20,'Thank you, next','Ariana Grande','Inglês','3');
