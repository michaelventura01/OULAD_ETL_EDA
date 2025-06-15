# OULAD_ETL_EDA
ETL para emplear un EDA con el consumo de la base de datos de posgress y mysql

#### Se requiere contar con el modelo de datos siguiente
<p>Es debido cargar en la base de datos mysql el contexto de datos de <b>SCRIPTS/script_sakila_mysql.sql</b></p>

```
├───OULAD_ETL
│       config.ini
│       config.py
│       database_operation.py
│       etl_operation.py
│       file_operation.py
│       main.py
│       requirements.txt
│
├───OULAD_REPORTERIA
│       config.ini
│       config.py
│       database_operation.py
│       file_operation.py
│       main.py
│       procesos.py
│       requirements.txt
│       user_interface.py
│
├───REPORTES_GENERADOS
└───SCRIPTS
        modelo_oulad.sql
        script_sakila_dwh_postgree.sql
        

```

<p>Para trabajar en el proyecto</p>

```
  # clonan proyecto
  git clone [enlace del proyecto .git]
  
  # validan todas las ramas remotas
  git fetch origin
  git branch -r
  
  # halan rama con su nombre
   git checkout -b master origin/main
  
  # actualzan rama con su nombre
  git pull origin/main

```

<p>Antes de empezar a trabajar</p>

```
  # actualizar su rama de la principal
  git merge master
```


<p>Una vez los cambios esten en su rama seran integrados manualmente a la rama main</p>
