FROM kalilinux/kali-rolling

RUN apt-get update && apt-get install -y \
    nmap \
    net-tools \
    curl \
    python3 \
    python3-pip \
    neovim \
    tmux

RUN pip3 install --upgrade pip

CMD ["/bin/bash"]

