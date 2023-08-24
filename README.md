Esta es el codigo para la base de datos.
Create database prueba;
use prueba;

Create table datos(
codigo int not null PRIMARY KEY,
cedula int  null,
Nombre varchar(50) null,
FechaN varchar(50) null,
Signo varchar(50) null
);

insert into datos
values
('2020202020','1752374239','Dennis','2003-08-23','Leo'),
('2121212121','1752374247','Amanda','2002-04-22','Virgo');

select * from datos;Create database prueba;
use prueba;

Create table datos(
codigo int not null PRIMARY KEY,
cedula int  null,
Nombre varchar(50) null,
FechaN varchar(50) null,
Signo varchar(50) null
);

insert into datos
values
('2020202020','1752374239','Dennis','2003-08-23','Leo'),
('2121212121','1752374247','Amanda','2002-04-22','Virgo');

select * from datos;
