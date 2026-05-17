FROM registry.ocp4.example.com:8443/ubi8/ubi
RUN dnf install -y python39 
WORKDIR /app
COPY script.sh .
RUN chmod +x script.sh
CMD ["/bin/bash","/app/script.sh"]

