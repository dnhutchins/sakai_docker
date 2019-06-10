FROM maven:3.6.1-jdk-8

RUN apt update && apt install shellinabox && echo "root:toor" | chpasswd

COPY bashrc /root/.bashrc

# wget https://storage.googleapis.com/google-code-archive-downloads/v2/code.google.com/shellinabox/shellinabox_2.10-1_amd64.deb -o /var/cache/apt/archives/shellinabox_2.10-1_amd64.deb && apt install shellinabox && rm /var/cache/apt/archives/shellinabox_2.10-1_amd64.deb


