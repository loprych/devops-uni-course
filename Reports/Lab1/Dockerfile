FROM fedora:latest

RUN dnf -y update && \
    dnf -y install git

WORKDIR /workspace

RUN git clone https://github.com/InzynieriaOprogramowaniaAGH/MDO2024_INO.git

CMD ["bash"]