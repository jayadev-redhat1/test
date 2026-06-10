FROM registry.ocp4.example.com:8443/ubi8/ubi
RUN dnf install -y python39 
ARG BINARY_URL="http://workstation.lab.example.com/script-bin"
WORKDIR /app
COPY $BINARY_URL ./script 
RUN chmod +x script
CMD ["/bin/bash","/app/script"]

