FROM strimzi/stunnel-base:latest

# exposing Zookeeper ports
EXPOSE 2181 2888 3888

# copy scripts for starting Stunnel
COPY ./scripts/ $STUNNEL_HOME

USER 1001

CMD ["/opt/stunnel/stunnel_run.sh"]
