FROM prom/alertmanager:latest

COPY conf/ /etc/alertmanager/

WORKDIR    /alertmanager
ENTRYPOINT [ "/bin/alertmanager" ]
CMD        [ "-config.file=/etc/alertmanager/alertmanager.yml", \
             "-storage.path=/alertmanager" ]
