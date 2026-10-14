# SQL1_postgres

# to run 4_query_csv.sql
podman exec -i postgres psql -U cassandra -d dba_db < 4_query_csv.sql | less -RS

# to run interactive postgres
podman exec -it postgres psql -U kokchun -d dba_db 
