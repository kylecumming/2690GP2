FROM dpage/pgadmin4:latest
WORKDIR /pgadmin
COPY . .
USER pgadmin
EXPOSE 4033
ENTRYPOINT ["/entrypoint.sh"]