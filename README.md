# menu
create table chefs(
chef id VARCHAR(10) not null,
name VARCHAR(30) not null,
reviews VARCHAR(100),
rating INTEGER,
active TINYINT(1) NOT NULL DEFAULT 1,
primary key(chef id)
);
create table menu (
item id INTEGER,
name  VARCHAR(10),
description VARCHAR (50),
quantity FLOAT NOT NULL DEFAULT 0,
price  INTEGER,
primary key(item id)
);
