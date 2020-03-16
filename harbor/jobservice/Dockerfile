FROM goharbor/harbor-jobservice:v1.9.4

USER root

VOLUME [/var/log/jobs/]

ENTRYPOINT ["/harbor/harbor_jobservice", "-c", "/etc/jobservice/config.yml"]

