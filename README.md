Dowload

https://www.pgadmin.org/download/

https://www.enterprisedb.com/downloads/postgres-postgresql-downloads

Commands

Créer une table:

create table schema.nom_de_la_future_table (
  nom_colone type,
  nom_colone2 type
)

Insérer une data dans une table:

insert into schema.nom_de_la_table
values ()

Regarder ce que contient une table:

select * from schema.nom_de_la_table

Ajouter une clé étrangère:

alter table schema.nom_de_la_table ADD CONSTRAINT nom_categorie FOREIGN KEY (nom_categorie) REFERENCES schema_de_la_table_en_question.nom_de_la_table ON UPDATE CASCADE ON DELETE CASCADE

Supprimer un élément d'une table:

DELETE FROM schema.nom_de_la_table
where nom_de_la_colone = valeur
