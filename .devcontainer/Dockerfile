# Use Fedora 38 as the base image
FROM fedora:38

# Install Java OpenJDK, python3-pip, and ansible
RUN dnf --assumeyes install git python3-pip python3-devel && \
    pip3 install ansible ansible-rulebook ansible-runner ansible-lint ansible-doc-extractor

RUN ansible-galaxy collection install google.cloud