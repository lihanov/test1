# test1
Use Ubuntu 20.04: 
 Fill out before doing  "grup_vars/ db_postgres.yml"  and  "hosts"

   ansible-playbook -i hosts postgres.yml


Result: 
 two instant:
  1. Base   : /var/lib/postgresql/12/main \n
     Config : /etc/postgresql/12/main \n
     Port   : 5433 \n

  2. Base   : /var/lib/postgresql/12/db2 
     Config : /etc/postgresql/12/db2
     Port   : 5432
