FROM postgres:14.1-bullseye

COPY scripts/001_Create_table.sql /docker-entrypoint-initdb.d/

ENTRYPOINT ["docker-entrypoint.sh"]
CMD ["postgres"]